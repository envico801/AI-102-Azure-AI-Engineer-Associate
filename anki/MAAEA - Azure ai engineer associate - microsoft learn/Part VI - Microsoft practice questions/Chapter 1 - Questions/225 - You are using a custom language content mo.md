========== Question ==========  

### You are using a custom Language content model in an Azure AI Video Indexer solution.

During testing, you upload a text file that includes the following sentence: “Kubernetes is a new feature in Azure & the cloud.”

The sentence is discarded.

You need to ensure that the model retains the sentence.

What should you do?

Select only one answer.

-   Change the model to a custom slate detection model.

-   Remove the “&” character from the text file.

-   Retrain the model.  

========== Answer ==========  

---

###### 1. Remove the “&” character from the text file.

You need to remove the “&” character because sentences with special characters will be discarded.

Kubernetes is highly specific and unknown to the model, so retraining the model is incorrect. The slate model is for clapper boards and digital patterns with color bars.

[Customize a Language model in Azure Video Indexer - Azure - Azure Video Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-video-indexer/customize-language-model-overview)

[Analyze video - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-video/)

========== Id ==========  
225

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#225-You-are-using-a-custom-language-content-mo

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
