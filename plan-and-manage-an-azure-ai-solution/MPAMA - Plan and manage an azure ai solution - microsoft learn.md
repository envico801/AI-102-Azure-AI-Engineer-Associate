# MPAMA - Plan and manage an azure ai solution - microsoft learn

## Questions

### Part I - Select the appropriate Azure AI services

#### Chapter 1 - Select the appropriate service for a generative AI solution

#### Chapter 2 - Select the appropriate service for a computer vision solution

#### Chapter 3 - Select the appropriate service for a natural language processing solution

#### Chapter 4 - Select the appropriate service for a speech solution

#### Chapter 5 - Select the appropriate service for an information extraction solution

#### Chapter 6 - Select the appropriate service for a knowledge mining solution

### Part II - Plan, create and deploy an Azure AI service

#### Chapter 1 - Plan for a solution that meets Responsible AI principles

#### Chapter 2 - Create an Azure AI resource

Q:: What type of AI focuses specifically on generating original content (like text, code, or images) based on input prompts?
A:: Generative AI.
Source: [What is AI?](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What is the term for the natural language input given to a generative AI model to elicit a response?
A:: Prompt.
Source: [What is AI?](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: What are the two general sizes/types of language models mentioned for generative AI?
A:: Large Language Models (LLMs) and Small Language Models (SLMs).
Source: [What is AI?](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

Q:: Which specific Azure AI Service provides access to OpenAI models like GPT and DALL-E within the Azure environment?
A:: Azure OpenAI Service.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI Service is primarily used for interpreting visual input from images or videos (e.g., object detection, reading text)?
A:: Azure AI Vision.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI Service deals with capabilities like speech-to-text and text-to-speech transformations?
A:: Azure AI Speech.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI Service focuses on analyzing natural language text for tasks like sentiment analysis, entity extraction, or summarization?
A:: Azure AI Language.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI Service helps detect potentially harmful, offensive, or undesirable content in text and images?
A:: Azure AI Content Safety.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure AI Service is specifically designed for extracting data and structure from documents like forms, invoices, and receipts?
A:: Azure AI Document Intelligence (formerly Form Recognizer).
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: Which Azure service is often used to create searchable indexes, potentially using AI skills, to support knowledge mining or grounding for generative AI?
A:: Azure AI Search.
Source: [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: What is the **recommended comprehensive platform** for developing AI solutions on Azure, encompassing tools, resource management, and project organization?
A:: Azure AI Foundry.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: In Azure AI Foundry, what is the **top-level container** used for managing shared resources, data, connections, and security configurations across multiple related projects?
A:: Hub.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: What is the primary benefit of defining resource connections at the Azure AI Foundry **Hub** level?
A:: Resources are shared and inherited by all **Projects** within that Hub, centralizing management and access.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: Within an Azure AI Foundry Hub, what is the workspace called where developers collaborate on building a **specific** AI solution?
A:: Project.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: Besides the Hub resource itself, what are three key Azure resource types typically created automatically when setting up an Azure AI Foundry Hub?
A:: A multi-service **Azure AI services** resource, an **Azure Key Vault**, and an **Azure Storage account**.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: What visual tool within Azure AI Foundry / Azure AI Studio allows developers to design, orchestrate, test, and manage the logic flow of interactions with generative AI models?
A:: Prompt Flow.
Source: [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: What is the primary SDK used to programmatically interact with Azure AI Foundry Hubs and Projects?
A:: Azure AI Foundry SDK (often referred to as the Azure AI SDK in this context).
Source: [Developer Tools and SDKs](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: What is the core principle of Responsible AI that emphasizes that AI systems should treat all people fairly and avoid bias?
A:: Fairness.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core principle of Responsible AI that dictates AI systems should perform dependably and safely?
A:: Reliability and Safety.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core principle of Responsible AI related to protecting user data and securing the AI system itself?
A:: Privacy and Security.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core principle of Responsible AI stating that AI systems should empower everyone and bring benefits to all parts of society?
A:: Inclusiveness.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core principle of Responsible AI requiring that users should be able to understand how an AI system works and its limitations?
A:: Transparency.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

Q:: What is the core principle of Responsible AI asserting that people are ultimately responsible for the design and impact of AI systems?
A:: Accountability.
Source: [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

#### Chapter 3 - Choose the appropriate AI models for your solution

#### Chapter 4 - Deploy AI models using the appropriate deployment options

#### Chapter 5 - Install and utilize the appropriate SDKs and APIs

#### Chapter 6 - Determine a default endpoint for a service

#### Chapter 7 - Integrate Azure AI services into a continuous integration and continuous delivery (CI/CD) pipeline

#### Chapter 8 - Plan and implement a container deployment

### Part III - Manage, monitor, and secure an Azure AI service

#### Chapter 1 - Monitor an Azure AI resource

#### Chapter 2 - Manage costs for Azure AI services

#### Chapter 3 - Manage and protect account keys

#### Chapter 4 - Manage authentication for an Azure AI Service resource

### Part IV - Implement AI solutions responsibly

#### Chapter 1 - Implement content moderation solutions

#### Chapter 2 - Configure responsible AI insights, including content safety

#### Chapter 3 - Implement responsible AI, including content filters and blocklists

#### Chapter 4 - Prevent harmful behavior, including prompt shields and harm detection

#### Chapter 5 - Design a responsible AI governance framework

---

DECK INFO

TARGET DECK: Azure::AI-102::MPAMA - Plan and manage an azure ai solution - microsoft learn

FILE TAGS: #Azure::#AI-102

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```
