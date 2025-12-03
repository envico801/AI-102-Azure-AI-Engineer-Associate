========== Question ==========  

### You are building an app that will use Azure AI Vision to analyze and classify images to build an image library of animals.

You need to configure the classification type for the Azure AI Vision project. The solution must ensure that the images selected only include a single animal.

Which type of classification should you use?

Select only one answer.

-   multiclass

-   multilabel

-   singleclass

-   singlelabel

-   unilabel  

========== Answer ==========  

---

###### 1. multiclass

Multilabel classification applies any number of tags to an image (zero or more), while multiclass classification sorts images into single categories (every image you submit will be sorted into the most likely tag). Therefore, using multilabel means that one image can be tagged as both “cat” and “dog” at the same time, although it should be either/or.

[Quickstart: Build an image classification model with the Custom Vision portal - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/getting-started-build-a-classifier)

[Classify images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/classify-images/)

========== Id ==========  
209

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#209-You-are-building-an-app-that-will-use-azur

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
