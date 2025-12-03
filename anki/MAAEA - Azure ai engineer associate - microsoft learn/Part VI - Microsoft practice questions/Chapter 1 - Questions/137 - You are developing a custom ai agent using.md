========== Question ==========  

### You are developing a custom AI agent using Azure AI Foundry Agent Service. The agent needs to interact with an Azure AI Foundry resource that has the GPT-35-Turbo model deployed.

You need to configure the agent to effectively use the GPT-35-Turbo model for generating responses.

What should you do?

Select only one answer.

-   Deploy a GPT-4 model.

-   Specify the GPT-35-Turbo deployment name.

-   Use the Completion endpoint.

-   Use the Embeddings endpoint.  

========== Answer ==========  

---

###### 1. Specify the GPT-35-Turbo deployment name.

To configure the agent to effectively use the GPT-35-Turbo model, specifying the deployment name ensures the agent interacts with the correct model deployed in a Microsoft Azure OpenAI resource. Using the Completion endpoint is not suitable for this model, as the ChatCompletion endpoint is preferred, and these endpoints aren't applicable to agents. Deploying a GPT-4 model does not meet the requirement to use the GPT-35-Turbo model specified in the scenario. The Embeddings endpoint is not appropriate for generating responses, as it serves a different purpose, such as creating vector representations of text.

[Get started with AI agent development on Azure - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

========== Id ==========  
137

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#137-You-are-developing-a-custom-ai-agent-using

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
