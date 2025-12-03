========== Question ==========  

### You build an app named App1 that uses the Azure AI Face service.

You need to optimize the app for images that contain blurry faces.

What should you do?

Select only one answer.

-   Change the recognition model to `recognition_02`.

-   Decrease the `faceIdTimeToLive` value.

-   Set the detection model to `detection_03`.  

========== Answer ==========  

---

###### 1. Set the detection model to `detection_03`.

Model_3 Improves accuracy on small, side-view, and blurry faces.

Changing the recognition model to recognition_02 will improve facial recognition and faceIdTimeToLive is used for the number of seconds that the face is cached, which has no impact on blurry faces.

[How to specify a detection model - Face - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/how-to/specify-detection-model)

[Detect, analyze, and recognize faces - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-analyze-recognize-faces/)

========== Id ==========  
232

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#232-You-build-an-app-named-app1-that-uses-the

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
