========== Question ==========  

### You are building a GPT-based chat application that will answer questions about your company.

You plan to use the Using your data feature in Azure OpenAI to ground the model with your company data.

While testing, you discover that some responses are not accurate enough.

You need to configure the Azure OpenAI resource to filter out less-relevant documents for responses.

Which parameter should you configure?

Select only one answer.

-   Content data

-   File name

-   Retrieved documents

-   Strictness  

========== Answer ==========  

---

###### 1. Strictness

The Strictness parameter sets the threshold to categorize documents as relevant to your queries. Raising the Strictness parameter value means a higher threshold for relevance and filters out more less-relevant documents for responses. Retrieved documents specifies the number of top-scoring documents from your data index used to generate responses. Content data specifies the fields in your index that contain the main text content of each document. File name specifies the field in your index that contains the original file name of each document.

[Using your data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/use-your-data?tabs=ai-search)

========== Id ==========  
195

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#195-You-are-building-a-gpt-based-chat-applicat

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
