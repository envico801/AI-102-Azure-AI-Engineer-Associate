========== Question ==========  

### You are building an orchestration workflow to orchestrate and connect multiple Language Understanding models and question answering projects for use in a bot.

Which two operations can you perform in an orchestration workflow based on Azure AI Language service? Each correct answer presents a complete solution.

Select all answers that apply.

-   Add entities to your orchestration workflow directly.

-   Connect to Language Understanding applications that are owned by the same resource as the orchestration workflow.

-   Connect to question answering projects that are in the same Azure AI Language service resource as your orchestration workflow.

-   Label a single word as two different entities.  

========== Answer ==========  

---

###### 1. Connect to Language Understanding applications that are owned by the same resource as the orchestration workflow.

###### 2. Connect to question answering projects that are in the same Azure AI Language service resource as your orchestration workflow.

Adding entities to your orchestration workflow is not allowed. Entities are mutually exclusive within an orchestration workflow.

[Frequently Asked Questions for orchestration projects - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/orchestration-workflow/faq)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

========== Id ==========  
180

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#180-You-are-building-an-orchestration-workflow

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
