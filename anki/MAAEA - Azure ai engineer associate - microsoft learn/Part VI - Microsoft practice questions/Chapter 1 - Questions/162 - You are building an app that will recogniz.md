========== Question ==========  

### You are building an app that will recognize the intent and entities of user utterances in real-time.

You need to implement the pattern matching intent recognition mechanism. The solution must only detect entities that you define in a catalog of phrases.

Which entity type should you use?

Select only one answer.

-   the List entity using Fuzzy mode

-   the List entity using Strict mode

-   the prebuilt entity using Fuzzy mode

-   the prebuilt entity using Strict mode

-   the regex entity using Fuzzy mode

-   the regex entity using Strict mode  

========== Answer ==========  

---

###### 1. the List entity using Strict mode

The List entity is made up of a list of phrases that will guide the engine on how to match the text. When an entity has an of type List and is in Strict mode, the engine will only match if the text in the slot appears in the list.

[Pattern Matching overview - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/pattern-matching-overview#types-of-entities)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

========== Id ==========  
162

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#162-You-are-building-an-app-that-will-recogniz

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
