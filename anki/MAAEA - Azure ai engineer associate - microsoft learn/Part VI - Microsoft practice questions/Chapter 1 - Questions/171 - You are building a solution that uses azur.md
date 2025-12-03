========== Question ==========  

### You are building a solution that uses Azure AI Search.

You need to create a skillset definition.

What are minimum sections you should include in the definition?

Select only one answer.

-   `name`, `description`, and `skills`

-   `name, description, knowledgeStore`, and `encryptionKey`

-   `name, description, skills`, and `cognitiveServices `

-   `name, description, skills, knowledgeStore`, and `encryptionKey`  

========== Answer ==========  

---

###### 1. `name`, `description`, and `skills`

Only `name`, `description`, and `skills` are required.

`cognitiveServices` is used for billable skills that call Cognitive Services APIs.

`knowledgeStore` specifies an Azure Storage account and the settings for projecting the skillset output into tables, blobs, and files in Azure Storage.

`encryptionKey` specifies an Azure key vault and customer-managed keys used to encrypt sensitive content (descriptions, connection strings, keys) in a skillset definition.

[Create a skillset - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-defining-skillset#add-a-skillset-definition)

[Create a custom skill for Azure Cognitive Search - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-enrichment-pipeline-azure-cognitive-search/)

========== Id ==========  
171

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#171-You-are-building-a-solution-that-uses-azur

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
