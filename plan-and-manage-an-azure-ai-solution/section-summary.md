## Plan and prepare to develop AI solutions on Azure

### 1. [What is AI?](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

*   **Simple Idea:** Artificial Intelligence (AI) is basically making computer software smart enough to do things that usually require human intelligence. Think of it like teaching a computer to see, talk, write, or make decisions based on information.
*   **How it Works Today:** Modern AI learns patterns from huge amounts of data (like learning from reading millions of books or seeing millions of pictures). This learning is stored in something called a *model*.
*   **What Can AI Do? (Common Capabilities):**
    *   **Generative AI:** Like a creative assistant. You ask it in plain English (a "prompt"), and it creates something new – like writing an email, a story, or even code.
        *   *Example:* Asking an AI to "Write a catchy description for a 3-bedroom house near a park."
    *   **Agents:** Think of this as Generative AI plus action. It doesn't just answer; it can *do* things for you based on your request.
        *   *Example:* An AI assistant that not only tells you where your meeting is but also books you a taxi to get there.
    *   **Computer Vision:** Giving computers "eyes." They can understand pictures and videos.
        *   *Example:* A supermarket checkout that automatically sees and identifies the groceries in your cart without scanning barcodes.
    *   **Speech:** Giving computers "ears" and a "mouth." They can understand spoken words and speak back.
        *   *Example:* Talking to Siri or Alexa – they understand your voice (speech-to-text) and reply (text-to-speech).
    *   **Natural Language Processing (NLP):** Teaching computers to understand human language (written or spoken).
        *   *Example:* Software that reads customer reviews online and figures out if they are positive or negative (sentiment analysis).
    *   **Information Extraction:** Like a super-fast assistant that reads documents, listens to recordings, or looks at images and pulls out the important bits.
        *   *Example:* Software that scans a photo of a receipt and automatically fills out your expense report with the date, items, and total cost.
    *   **Decision Support:** Using past data to predict what might happen next, helping humans make better decisions.
        *   *Example:* Analyzing past sales data and weather patterns to predict how much ice cream a shop should stock next week.

### 2. [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

*   **Simple Idea:** Microsoft Azure (their cloud computing platform) offers ready-made AI tools, like building blocks. Instead of building an AI brain from scratch (which is super hard!), you can use these pre-built services.
*   **Examples of these "AI Building Blocks":**
    *   **Azure OpenAI:** Access to powerful Generative AI models (like the ones behind ChatGPT) for writing, coding, etc.
    *   **Azure AI Vision:** For computer "seeing" tasks (analyzing images, reading text in photos).
    *   **Azure AI Speech:** For computer "talking" and "listening."
    *   **Azure AI Language:** For understanding text (like finding key topics or sentiment).
    *   **Azure AI Content Safety:** Checks text and images for harmful or inappropriate content.
    *   **Azure AI Translator:** Translates text between languages.
    *   **(Others):** Services for recognizing faces, building custom "seeing" models, reading forms/documents, and searching information smartly.
*   **How You Use Them:**
    *   You can pick just the service you need (like only Vision) or get a bundle of common services together in one package (**multi-service resource**).
    *   These services might not be available everywhere in the world (**regional availability**).
    *   You pay based on how much you use them (**cost**).

### 3. [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

*   **Simple Idea:** Think of AI Foundry as the **workshop** or **office space** where teams build their AI solutions using Azure's tools. It helps keep everything organized, secure, and managed properly, especially for bigger projects.
*   **Key Concepts:**
    *   **Hub:** Imagine this as the main department office (e.g., the Marketing AI Department Hub). It holds shared resources (like expensive tools everyone needs – e.g., access to the powerful Azure OpenAI service), manages who is allowed in (security), and keeps track of shared data or connections. An IT admin usually sets up the Hub.
    *   **Project:** Within the Hub (the department), each specific task or application gets its own "project room" (e.g., the "Customer Review Analyzer" project room). The team working on that specific AI application collaborates here. They use the shared tools from the Hub, and might have some specific tools or data just for their project.
*   **Why Use It?** It makes teamwork easier, centralizes management of expensive resources (like the AI models), controls costs, and keeps things secure. It's the recommended way to build serious AI applications on Azure.

### 4. [Developer Tools and SDKs](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

*   **Simple Idea:** To actually build the AI applications using the Azure services and Foundry, developers need tools to write the instructions (code).
*   **Common Tools:**
    *   **Code Editors:** Like Microsoft Word, but for writing code (e.g., Visual Studio Code). Azure AI Foundry even offers a pre-set VS Code environment ready to go.
    *   **GitHub:** A place where developers store their code, share it with teammates, and track changes (like a shared folder with version history for code).
    *   **GitHub Copilot:** An AI assistant that helps developers write code faster (like predictive text, but for programming).
    *   **SDKs (Software Development Kits):** These are like special toolkits or libraries that make it easier for developers to use specific Azure AI services or features (like the AI Foundry tools or the Speech service) within their code, without needing to write everything from the ground up.

### 5. [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

*   **Simple Idea:** Building AI is powerful, so it's incredibly important to do it ethically and responsibly. Think "AI for Good."
*   **Key Principles (Think checklist for doing AI right):**
    *   **Fairness:** The AI shouldn't be biased against any group of people. (e.g., a loan approval AI shouldn't discriminate based on race or gender).
    *   **Reliability & Safety:** The AI should work correctly and not cause harm. (e.g., AI in a self-driving car must be reliable).
    *   **Privacy & Security:** The AI must protect people's personal information.
    *   **Inclusiveness:** The AI should be designed to benefit everyone, including people with disabilities.
    *   **Transparency:** It should be clear how the AI works and what its limitations are. People should know when they are interacting with an AI.
    *   **Accountability:** Humans should be responsible for how AI systems are built and used. Someone needs to be accountable if things go wrong.

### 6. Module Assessment Question Simplified ([Source: Module assessment](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/8-knowledge-check))

*   **Question:** If developers need access to the *same* tools (resources) for *multiple* different AI projects, what's the best way to set that up using Azure AI Foundry?
*   **Answer Explained:** Instead of giving access separately in *each* project room (which is repetitive and hard to manage), you should put the connection to those shared tools in the main "office building" – the [**Azure AI Foundry hub**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry). That way, anyone working on any project within that hub automatically gets access to those shared tools.

### In a Nutshell:

Azure helps you build smart AI applications. It gives you pre-built AI "Lego blocks" ([**Azure AI Services**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)). To manage your building process, especially for teams, you use a structured "workshop" called [**Azure AI Foundry**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry) (with [**Hubs**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry) for shared stuff and [**Projects**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry) for specific tasks). Developers use coding [**Tools & SDKs**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks) to put it all together. And crucially, everyone involved needs to think about building AI [**Responsibly**](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai) so it's fair, safe, and beneficial.
