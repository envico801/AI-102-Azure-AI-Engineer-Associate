========== Question ==========  

### You are building an app that uses Azure AI Video Indexer.

You need to extract keyframes from uploaded video and store them on a disk by using the API.

How should you implement the solution?

Select only one answer.

-   Upload the video and download the ZIP file of the thumbnails.

-   Upload the video, download the ZIP file of the thumbnails, and get the thumbnail for each keyframe.

-   Upload the video, get the video index, and get the thumbnail for each keyframe.  

========== Answer ==========  

---

###### 1. Upload the video, get the video index, and get the thumbnail for each keyframe.

You need to upload the video, get the video index, and get the thumbnail for each keyframe. Three API calls need to be done.

Uploading the video and then downloading the ZIP file of the thumbnails is the path through the Azure portal. You need the index to know the correct parameters for the thumbnail request.

[Analyze video - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/analyze-video/)

========== Id ==========  
170

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#170-You-are-building-an-app-that-uses-azure-ai

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
