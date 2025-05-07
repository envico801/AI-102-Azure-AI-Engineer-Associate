# Secure Azure AI services

## 1. [Introduction](https://learn.microsoft.com/en-us/training/modules/secure-ai-services/1-introduction)

*   **Simple Idea:** Azure AI services have different ways to keep them safe. This part of the guide will teach you about two main security aspects:
    1.  **Authentication:** How your apps prove they are allowed to use the AI service (like showing an ID).
    2.  **Network Security:** How you control which computers or networks can even reach your AI service (like putting up a fence and a gate).

## 2. [How Your Apps Prove Who They Are (Authentication)](https://learn.microsoft.com/en-us/training/modules/secure-ai-services/2-authentication)

*   **The Basic Way: Subscription Keys (Like a Secret Password)**
    *   When you create an AI service, you get secret "keys." Your app needs to send one of these keys with every request to prove it's legitimate.
    *   **Problem:** If this key gets stolen or shared, bad actors can use your AI service and run up your bill!
*   **Keeping Keys Safe:**
    *   **Regenerate Keys Regularly (Change Your Password):** You should change these keys often. Azure gives you two keys so you can:
        1.  Tell all your apps to use Key 1.
        2.  Change Key 2 (make a new one).
        3.  Tell all your apps to now use the new Key 2.
        4.  Change Key 1.
        5.  Now you can use either new key. This way, your service doesn't stop working while you're updating.
    *   **Azure Key Vault (A Secure Safe):** Instead of putting the secret key directly in your app's code (where someone might find it), you can store it in Azure Key Vault.
        *   Your app gets a special, secure ID (called a **managed identity** or **service principal**).
        *   The app uses its ID to ask Key Vault for the secret key when it needs it.
        *   *Benefit:* The key is not lying around in your app's files.
*   **Another Way: Token-Based Authentication (A Temporary Pass)**
    *   For some services, your app first sends the subscription key to get a temporary "token" (like a short-term access badge).
    *   This token is usually valid for a short time (e.g., 10 minutes).
    *   For the next 10 minutes, your app sends the token instead of the main key.
    *   *Benefit (if using an SDK):* The SDK often handles this for you automatically.
*   **A More Advanced Way: Microsoft Entra ID Authentication (Like a Company ID Badge)**
    *   This is a more robust way to control access, especially for bigger setups or when using tools like Azure AI Foundry. Instead of just a shared secret key, access is tied to specific identities managed by Microsoft Entra ID (Azure's main identity service).
    *   **Two Main Types:**
        1.  **Service Principals (Giving an App its Own ID):**
            *   You register your application with Microsoft Entra ID.
            *   This creates a unique "service principal" for your app (like giving the app its own official employee ID badge).
            *   You then grant specific permissions (like "Cognitive Services User") to this service principal for your AI service.
            *   *Custom Subdomain:* Often, to use Entra ID, your AI service needs a unique, custom part in its web address (subdomain).
        2.  **Managed Identities (Giving Azure Resources an Automatic ID):**
            *   If your app is running on an Azure service (like a Virtual Machine), Azure can automatically create and manage an ID for that service.
            *   **System-assigned:** The ID is tied to that specific Azure resource (e.g., that one VM). If you delete the VM, the ID goes too.
            *   **User-assigned:** You create an ID that can be shared by multiple Azure resources.
            *   You then grant permissions to this managed identity (e.g., allow the VM's managed identity to use your AI service).
            *   *Benefit:* No passwords or keys to manage for that app/resource directly; Azure handles it.

## 3. [Controlling Who Can Reach Your AI Service (Network Security)](https://learn.microsoft.com/en-us/training/modules/secure-ai-services/3-implement-network-security)

*   **Default Setting: Open to Everyone (Risky!)**
    *   By default, your Azure AI service can be reached from any computer on the internet if they have the key. This is often not what you want.
*   **Making it More Secure (Putting Up Fences):**
    *   You can change the settings so that, by default, **no one** can access it. Then, you specifically allow access only from places you trust.
    *   **Options to Allow Access:**
        1.  **Selected Networks (Allowing Specific Office Networks/VPNs):**
            *   You can allow access only from specific Azure **Virtual Networks** (your private networks in Azure).
            *   You can allow access from specific **IP addresses** or ranges of IP addresses (like your company's office internet connection).
            *   *If you are doing this, it's a good idea to add your own computer's IP address if you need to test, or the network your app runs on.*
        2.  **Private Endpoints (A Private, Direct Tunnel):**
            *   This creates a private network connection directly from your virtual network to the AI service. It's like having a private road that doesn't go over the public internet. This is very secure.
            *   If you use *only* private endpoints, you can set the main network access to "Disabled" for maximum security.
        3.  **Disabled (Most Restrictive):** Blocks all public internet traffic. You would typically use this if you are *only* using Private Endpoints.
*   **Exceptions for Trusted Azure Services (VIP Pass for Other Azure Tools):**
    *   Some other Azure services (like Azure Machine Learning or Azure AI Search) might need to talk to your AI service.
    *   You can create an exception to let these "trusted services" access your AI service, even if you've restricted general network access. They usually use their own managed identities to authenticate.

## 4. [Trying It Out (Exercise)](https://learn.microsoft.com/en-us/training/modules/secure-ai-services/4-exercise-secure-ai-services)

*   **Simple Idea:** This section points you to a hands-on exercise where you can practice setting up these security features:
    *   Maybe regenerate keys.
    *   Set up network restrictions (like allowing only your virtual network or a specific IP).
    *   Potentially create a private endpoint.
*   **Reminder:** Delete resources after the exercise to avoid costs!

## 5. [Module Assessment Question Simplified](https://learn.microsoft.com/en-us/training/modules/secure-ai-services/5-knowledge-check)

*   **Question:** Your computer code can't connect to your Azure AI Service. It says "access denied due to Virtual Network/Firewall rules." What do you need to change in the AI Service's settings?
*   **Answer Explained:** The error message itself tells you the problem is with the "Virtual Network/Firewall rules." This means the AI service is set up to block most connections, and your computer's network/IP address isn't on the allowed list.
    *   You need to go to the **Networking properties** of the AI service.
    *   If it's set to "Selected Networks and Private Endpoints" (or even "Disabled" if you're not using private endpoints correctly for this scenario), you'll need to **add your client IP address to the Firewall allowed list.** This explicitly tells Azure, "It's okay for *this specific computer* to connect."
