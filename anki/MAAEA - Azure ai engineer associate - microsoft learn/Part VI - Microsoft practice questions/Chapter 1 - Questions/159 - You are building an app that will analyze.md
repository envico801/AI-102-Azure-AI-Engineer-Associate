========== Question ==========  

### You are building an app that will analyze resumes and remove names and addresses.

You need to configure the Azure AI Language Personally Identifiable Information (PII) detection feature for the app.

Which categories should you specify in the request?

Select only one answer.

-   Person, Address, and IP

-   Person and Address only

-   Person, PersonType, and Address  

========== Answer ==========  

---

###### 1. Person and Address only

Person and Address will detect names and addresses.

PersonType will also remove job roles. IP will also remove IP addresses.

[Entity categories recognized by Personally Identifiable Information (detection) in Azure Cognitive Service for Language - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/personally-identifiable-information/concepts/entity-categories)

[Publish and use a Language Understanding app - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/publish-use-language-understand-app/)

========== Id ==========  
159

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#159-You-are-building-an-app-that-will-analyze

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
