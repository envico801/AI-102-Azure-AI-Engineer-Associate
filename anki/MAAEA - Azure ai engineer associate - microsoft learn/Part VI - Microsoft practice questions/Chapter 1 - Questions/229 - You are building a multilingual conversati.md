========== Question ==========  

### You are building a multilingual conversational app by using Conversational Language Understanding (CLU), part of Azure AI Language service.

You create a CLU model that will serve multiple languages.

You need to optimize the performance of the model. The solution must minimize development effort.

What should you do?

Select only one answer.

-   Add utterances for languages that are performing poorly in the model.

-   Configure the app to only query utterances in the language that was used to train the model.

-   Create separate projects for each language.

-   Train the model by using utterances in multiple languages and only query the model by using the project language.  

========== Answer ==========  

---

###### 1. Add utterances for languages that are performing poorly in the model.

With CLU, there is no need to use multiple projects for a model. For example, you can train a model in English and query it in German. There is no project language, therefore, adding utterances for languages in the model that are performing poorly is the appropriate solution to increase performance.

[Multilingual projects - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/conversational-language-understanding/concepts/multiple-languages)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

========== Id ==========  
229

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#229-You-are-building-a-multilingual-conversati

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
