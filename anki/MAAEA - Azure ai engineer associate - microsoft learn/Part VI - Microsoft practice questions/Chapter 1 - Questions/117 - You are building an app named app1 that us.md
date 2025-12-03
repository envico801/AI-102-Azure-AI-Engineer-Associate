========== Question ==========  

### You are building an app named App1 that uses the Image Analysis API.

You are evaluating analyzing images by using the following request.

`https://*.cognitiveservices.azure.com/computervision/imageanalysis:analyze? features=read,description`

Which results will the request return?

Select only one answer.

-   a description of the image content only

-   the visible text in the image and a description of the image content

-   which objects there are in the image and their approximate location  

========== Answer ==========  

---

###### 1. the visible text in the image and a description of the image content

The features used in the call are `read` and `description`, which will return the visible text in the image, as well as a description of the image content.

To return the objects that are in the image and their approximate location, the feature used in the call should be `objects`. To return a description of the image content only, the feature `description` should be used alone.

[Call the Image Analysis API - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/how-to/call-analyze-image?tabs=rest)

[Read Text in Images and Documents with the Computer Vision Service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-images-documents-with-computer-vision-service/)

========== Id ==========  
117

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#117-You-are-building-an-app-named-app1-that-us

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
