========== Question ==========  

### You are deploying an Azure OpenAI in Foundry Models service.

You plan to use your own data in the models you will deploy.

You need to ensure that the model can index your data sources.

Which additional Azure service should you deploy?

Select only one answer.

-   Azure AI Search

-   Content Moderator

-   Language

-   Personalizer  

========== Answer ==========  

---

###### 1. Azure AI Search

Azure OpenAI on your data enables developers to use supported AI chat models that can reference specific sources of information to ground the response. Adding this information allows the model to reference both the specific data provided and its pretrained knowledge to provide more effective responses. Azure OpenAI on your data utilizes the search ability of Azure AI Search to add the relevant data chunks to a prompt.

Azure OpenAI on your data still uses a stateless API to connect to the model, which removes the requirement of training a custom model with your data and simplifies the interaction with the AI model. Cognitive Search first finds the useful information to answer the prompt, and Azure OpenAI forms the response based on that information.

[Develop a RAG-based solution with your own data using Azure AI Foundry - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/)

[What are Azure AI services? - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/what-are-ai-services)

========== Id ==========  
226

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#226-You-are-deploying-an-azure-openai-in-found

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
