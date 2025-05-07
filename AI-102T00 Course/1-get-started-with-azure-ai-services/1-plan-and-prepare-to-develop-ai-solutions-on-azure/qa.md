Q:: What is the fundamental goal of Artificial Intelligence (AI)?
A:: To create computer software capable of performing tasks that typically require human intelligence, such as reasoning, learning, seeing, understanding language, and making decisions. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: How do modern AI systems typically learn, and what is the result of this learning process called?
A:: Modern AI learns by identifying patterns in vast amounts of data. This learned knowledge is stored in a structure called a *model*. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What AI capability focuses on creating *new* content (like text, stories, or code) in response to a user's natural language request, often called a "prompt"?
A:: Generative AI. It acts like a creative assistant, generating novel output based on the input prompt. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: How does an AI Agent build upon the capabilities of Generative AI? What key function does it add?
A:: An AI Agent extends Generative AI by not just generating responses but also taking *actions* in the real or digital world based on the user's request (e.g., booking a taxi, not just suggesting one). [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: Which AI capability gives computers the ability to interpret and understand information from images and videos, essentially acting like digital "eyes"?
A:: Computer Vision. It allows systems to analyze visual input, like identifying objects in a picture or video feed. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What AI capability involves both understanding human spoken language (speech-to-text) and generating audible responses (text-to-speech)?
A:: Speech. This capability allows computers to function like digital "ears" and a "mouth," enabling voice interaction. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: Which AI capability focuses specifically on enabling computers to understand the *meaning*, structure, and intent within human language (written or spoken), going beyond just converting speech to text?
A:: Natural Language Processing (NLP). It's used for tasks like sentiment analysis, language translation, and understanding commands. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What is the primary goal of the Information Extraction AI capability when applied to documents, recordings, or images?
A:: Its primary goal is to automatically identify and pull out specific, important pieces of information (like dates, names, totals, keywords) from unstructured or semi-structured data sources. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: How does the Decision Support AI capability typically use past data, and what is its main purpose?
A:: It analyzes historical data to identify patterns and make predictions about future outcomes, aiming to help humans make more informed and better decisions. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: If an AI system analyzes customer reviews to determine if they are generally positive or negative, which core AI capability is primarily being used?
A:: Natural Language Processing (NLP), specifically a technique often called sentiment analysis. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What is the fundamental advantage of using Azure AI Services compared to building AI capabilities entirely from scratch?
A:: Azure AI Services provide pre-built, ready-to-use AI tools and models ("building blocks") via the cloud, significantly reducing the complexity and effort required to integrate AI features into applications. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which specific Azure AI service grants access to powerful large language models for tasks like content generation, summarization, and code writing?
A:: Azure OpenAI provides access to these powerful Generative AI models. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: If an application needed to implement computer "seeing" functionalities, such as analyzing image content or recognizing text within pictures, which Azure AI service would be the primary choice?
A:: Azure AI Vision is designed for computer vision tasks like image analysis and optical character recognition (OCR). [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: For enabling applications to understand spoken language or generate synthesized speech, which Azure AI service provides the necessary capabilities?
A:: Azure AI Speech offers services for speech-to-text conversion and text-to-speech synthesis. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: What Azure AI service focuses on processing and understanding the meaning within written text, for example, to identify key phrases or determine sentiment?
A:: Azure AI Language provides tools for natural language processing tasks on text data. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI service is specifically designed to help moderate content by identifying potentially unsafe or inappropriate material in text and images?
A:: Azure AI Content Safety is used for detecting and filtering harmful content. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: If an application requires multiple AI capabilities (e.g., vision, speech, and language), what Azure resource type allows consolidating access under a single endpoint and key?
A:: A **multi-service resource** (often referred to as an Azure AI Services resource) bundles several common AI services together for simplified management. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Beyond the specific AI functionality offered, what is a key geographical consideration when deciding to use a particular Azure AI service?
A:: **Regional availability** – not all Azure AI services are available in every Azure datacenter region around the world. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: How is the financial aspect of using Azure AI Services typically structured?
A:: The **cost** is generally based on consumption, meaning you pay for the amount of the service you actually use (pay-as-you-go). [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: What is the core function of Azure AI Foundry in the context of developing AI solutions on Azure?
A:: Azure AI Foundry serves as an organizational and management structure ("workshop" or "office space") to streamline collaboration, centralize resource management (like AI models), control costs, and ensure security for AI development projects. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: Within Azure AI Foundry, what construct acts as the central container for shared resources, security policies, and data connections, typically managed by an administrator?
A:: The **Hub**. It serves as the top-level organizational unit, analogous to a main department office, holding shared assets for multiple projects. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: How does an AI Foundry **Project** relate to an AI Foundry **Hub**?
A:: A **Project** exists *within* a Hub and represents the dedicated workspace for a specific AI application or task. Teams work within Projects, utilizing shared resources from the parent Hub while also managing project-specific assets. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: What are the primary benefits of using the Azure AI Foundry structure for building AI applications?
A:: Key benefits include improved teamwork, centralized control over shared (often expensive) AI resources, better cost management, and enhanced security for AI development efforts. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: What general category of software tool do developers use to write, edit, and manage the programming instructions (code) for AI applications?
A:: **Code Editors** (like Visual Studio Code) are used for writing and managing application code. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: What platform provides essential services for storing code, tracking changes over time (version control), and enabling collaboration among developers working on AI projects?
A:: **GitHub** is widely used for code storage, version control, and team collaboration. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: What specific tool acts as an AI-powered programming assistant, helping developers write code more quickly and efficiently directly within their code editor?
A:: **GitHub Copilot** provides AI-driven code suggestions and autocompletions. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: What is the purpose of using **SDKs** (Software Development Kits) when interacting with Azure AI services from within application code?
A:: SDKs provide pre-written code libraries and tools that simplify the process for developers to integrate and use specific Azure AI service features (like Speech, Vision, or Foundry capabilities) in their applications, reducing the need to write low-level interaction code manually. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: What is the fundamental motivation behind the concept of Responsible AI?
A:: To ensure that powerful AI technologies are developed and deployed ethically, safely, and in ways that benefit society while mitigating potential harms. It's about prioritizing "AI for Good." [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: Why is the principle of **Fairness** critical when building AI systems, especially those making decisions about people?
A:: To prevent the AI from reflecting or amplifying societal biases, ensuring it doesn't discriminate against individuals or groups based on attributes like race, gender, or other protected characteristics. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What potential negative outcome does the **Reliability & Safety** principle aim to avoid in AI systems?
A:: It aims to prevent AI systems from malfunctioning, performing unpredictably, or causing unintended harm, particularly in critical applications like autonomous vehicles or medical diagnostics. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: How does the **Privacy & Security** principle guide the handling of data within AI systems?
A:: It requires that AI systems respect user privacy and securely manage the data they collect and process, protecting it from unauthorized access or breaches. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core objective of the **Inclusiveness** principle in responsible AI development?
A:: To ensure that AI systems are designed to be accessible, usable, and beneficial to all segments of society, including people with diverse needs and abilities. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: Why is **Transparency** considered essential for trustworthy AI?
A:: Transparency helps users and developers understand how an AI system arrives at its conclusions, what its capabilities and limitations are, fostering trust and enabling informed interaction. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What does the principle of **Accountability** establish regarding the development and deployment of AI?
A:: It establishes that humans are ultimately responsible for AI systems, ensuring that there are mechanisms for oversight, governance, and redress if the AI causes harm or operates improperly. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: In Azure AI Foundry, why is configuring access to shared tools or data connections at the **Hub** level generally preferred over configuring them individually in each **Project**?
A:: Centralizing shared resource connections within the **Hub** simplifies management, ensures consistency across multiple projects, streamlines access control, and avoids repetitive configuration within each separate project workspace. [Source](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)
