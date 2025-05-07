# Create and consume Azure AI services

## 1. [Introduction](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/1-introduction)

*   **Simple Idea:** Azure AI services are like a collection of pre-built smart tools in the cloud. You don't get just one big "AI thing"; you get individual services for different tasks (like seeing, speaking, understanding language, finding things, or even generating new content).
*   **Examples (again, good to remember):**
    *   **Azure AI Vision:** For understanding pictures and videos.
    *   **Azure AI Language:** For apps that need to understand human language.
    *   **Azure AI Speech:** For converting speech to text and text to speech.
    *   **Azure AI Document Intelligence:** For reading and understanding forms (like invoices).
    *   **Azure AI Search:** For super-smart searching through your data.
    *   **Azure AI Foundry:** (We discussed this before) For accessing generative AI models.
*   **The Point of This Section:** Even though each service does something different, the way you *set them up* and *use them* in your applications is generally very similar. This part of the guide will show you how.

## 2. [Getting an AI Service Ready (Provisioning)](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/2-create-ai-service-resource)

*   **Simple Idea:** Before your application can use an AI service, you need to "create" or "set up" that service in your Azure account. This is called **provisioning a resource**. This setup gives you:
    *   An address where your app can find the service (the endpoint).
    *   A secret password for your app to use (access keys).
    *   A way for Azure to bill you for using it.
*   **Your Choices When Setting Up:**
    *   **Multi-service resource (The Big Toolbox):** You can create one "AI services" resource that bundles many different AI tools together (like Language, Vision, Speech all in one).
        *   *Benefit:* One address, one set of secret keys, one bill for multiple services.
    *   **Single-service resource (Individual Tools):** You can create separate resources for each AI service you need (e.g., just an "AI Language" resource).
        *   *Benefit:* Separate addresses if needed (maybe for different world regions), separate keys for each, and separate billing. Often has a *free version* to try things out.
    *   **Special Case: Training vs. Using:** Some AI services, especially if you're customizing them, might have one resource for "teaching" the AI (training) and another for when your app "uses" what the AI learned (prediction). This helps manage costs for the teaching part separately.

## 3. [What Your App Needs to Connect (Endpoints and Keys)](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/3-identify-keys-endpoints)

*   **Simple Idea:** Once you've set up an AI service, your application needs three key pieces of information to use it:
    *   **Endpoint URI (The Address):** This is the specific internet address (like a website URL) where the AI service "lives." Your app sends its requests here.
        *   *Example:* `https://your-ai-service-name.cognitiveservices.azure.com/`
    *   **Subscription Key (The Secret Password):** To use the service, your app must send this secret key along with its request. It proves your app is allowed to access the service. You usually get two keys, so you can use one while you update the other without stopping your app.
    *   **Resource Location (The City):** This is the geographical region (like "East US" or "West Europe") where your AI service is running in an Azure data center. Some tools might need this in addition to the address.

## 4. [How Your App Talks to the AI Service - Method 1: REST API](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/4-use-rest)

*   **Simple Idea:** A REST API is a standard way for computer programs to talk to each other over the internet.
*   **How it Works:**
    *   Your application creates a message, usually in a specific format called **JSON** (which is just a way to structure data in text).
    *   It sends this message (an **HTTP request**) to the AI service's **endpoint address**.
    *   The AI service does its job (like analyzing an image you sent data about).
    *   The AI service sends a reply back (an **HTTP response**), also often in JSON format, containing the results.
*   **Analogy:** Think of it like sending a very detailed, structured order form (JSON) via a special postal service (HTTP) to a smart processing center (the AI service). The center processes your order and sends back a detailed confirmation slip (JSON response).
*   **Why it's common:** Almost any programming language or tool can send and receive these HTTP messages with JSON.

## 5. [How Your App Talks to the AI Service - Method 2: SDK](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/5-use-sdk)

*   **Simple Idea:** While you *can* use the REST API (sending those JSON "letters"), it's often much easier for developers to use an **SDK (Software Development Kit)**.
*   **What it is:** An SDK is a pre-packaged set of tools and libraries specifically designed for a particular programming language (like Python, C#, JavaScript, etc.). It makes using the AI service from that language simpler.
*   **How it Helps:** Instead of the developer having to manually create the JSON messages and handle the HTTP requests and responses, the SDK provides ready-made functions. The developer just calls these functions, and the SDK does the complicated "talking to the AI service" part in the background.
    *   The diagram shows this: the app uses the SDK, and the SDK handles the JSON request/response to the Azure AI service.
*   **Analogy:** If REST API is like writing a detailed letter from scratch, an SDK is like having a set of pre-written letter templates and an assistant who knows how to format and send them correctly for you. You just fill in the important bits.

## 6. [Trying It Out (Exercise)](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/5a-exercise-ai-services)

*   **Simple Idea:** This section points you to a hands-on exercise. If you have an Azure subscription, you can follow instructions (often on a provided virtual machine or your own computer if you set it up) to:
    1.  Create an Azure AI service resource.
    2.  Find its endpoint and keys.
    3.  Write a small piece of code (using an SDK or maybe a simple REST tool) to actually use the service and see it work.
*   **Important Tip:** After you're done with exercises, always remember to **delete the Azure resources** you created so you don't get charged for them when you're not using them!

## 7. [Module Assessment Question Simplified](https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/6-knowledge-check)

*   **Question:** How are client applications (your apps) typically granted access to an Azure AI Services endpoint (the service's address)?
*   **Answer Explained:** The application must send a **valid subscription key** (the secret password) for that Azure AI service. This key proves the app is authorized to use the service.

