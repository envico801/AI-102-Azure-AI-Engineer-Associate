========== Question ==========  

### You are configuring a question answering solution.

You execute the following API call and receive the following error.

```JSON
"synonyms": [

        {

            "alterations": [

                "fix problems",

                "troubleshoot",

                "#diagnostic",

                ]

        },

...
```

You need to ensure that the API call executes successfully.

What should you do?

Select only one answer.

-   Modify the order of the synonyms.

-   Remove any question and answer pairs from the call.

-   Remove any special characters from the call.  

========== Answer ==========  

---

###### 1. Remove any special characters from the call.

Special characters are not allowed for synonyms.

Synonyms can be added in any order, and the ordering is not considered in any computational logic. Synonyms can only be added to a project that has at least one question and answer pair.

[Improve the quality of responses with synonyms - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/tutorials/adding-synonyms)

[Build a question answering solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

========== Id ==========  
236

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#236-You-are-configuring-a-question-answering-s

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
