========== Question ==========  

### Your organization plans to implement a generative AI solution to assist the customer success by summarizing customer complaints and questions.

You need to ensure the model provides accurate summaries while reducing costs.

What action should you take?

Select only one answer.

-   Apply prompt engineering without external data sources.

-   Deploy a model without grounding data and rely on pre-trained capabilities.

-   Fine-tune a model using customer query data without an orchestration layer.

-   Use Retrieval-Augmented Generation (RAG) with Azure AI Search for grounding data.  

========== Answer ==========  

---

###### 1. Use Retrieval-Augmented Generation (RAG) with Azure AI Search for grounding data.

Using Retrieval-Augmented Generation (RAG) with Azure AI Search ensures the model provides accurate and contextually relevant summaries by incorporating domain-specific data. Deploying a model without grounding data relies solely on pre-trained capabilities, resulting in less accurate outputs. Fine-tuning a model without an orchestration layer fails to dynamically integrate real-time contextual data, limiting its effectiveness, and is significantly more expensive. Applying prompt engineering without external data sources improves response quality but does not address the need for domain-specific grounding.

[Understand how to ground your language model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/2-ground-language-model)

========== Id ==========  
201

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#201-Your-organization-plans-to-implement-a-gen

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
