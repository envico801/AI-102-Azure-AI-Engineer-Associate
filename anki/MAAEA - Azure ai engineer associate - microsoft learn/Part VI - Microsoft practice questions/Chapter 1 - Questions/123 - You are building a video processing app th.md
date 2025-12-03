========== Question ==========  

### You are building a video processing app that will use Azure AI Video Indexer.

You need to configure the training and learning phases for the app. The solution must train the model based on the probability of specific word combinations by using a custom Language model.

Which three practices should be followed for the training data? Each correct answer presents a complete solution.

Select all answers that apply.

-   Include at least 500,000 sentences.

-   Include multiple examples of spoken sentences.

-   Include special characters such as ~, #, @, %, and &.

-   Provide multiple adaptation options.

-   Put only one sentence per line.

-   Repeat the identical sentence multiple times.  

========== Answer ==========  

---

###### 1. Include multiple examples of spoken sentences.

###### 2. Provide multiple adaptation options.

###### 3. Put only one sentence per line.

When training the model, you should avoid repeating an identical sentence multiple times, as it may create bias against the rest of the input.

You should avoid including uncommon symbols (~, # @ % &), as they will be discarded. The sentences in which they appear will also be discarded.

You should also avoid putting inputs that are too large, such as hundreds of thousands of sentences, because doing so will dilute the effect of boosting.

[Customize a Language model in Azure Video Indexer - Azure - Azure Video Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-video-indexer/customize-language-model-overview)

[Analyze video - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-video/)

========== Id ==========  
123

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#123-You-are-building-a-video-processing-app-th

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
