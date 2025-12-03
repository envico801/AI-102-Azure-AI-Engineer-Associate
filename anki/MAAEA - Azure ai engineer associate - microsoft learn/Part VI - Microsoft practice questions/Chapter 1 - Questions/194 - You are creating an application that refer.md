========== Question ==========  

### You are creating an application that references the Azure OpenAI REST API for a DALL-E model.

You plan to use thumbnails of the images that DALL-E generates and display them in a table on a webpage.

You need to find the image URLs in the JSON response.

Which element should you review?

Select only one answer.

-   the ids array element

-   the images array element

-   the imageURL array element

-   the result element  

========== Answer ==========  

---

###### 1. the result element

The result from the initial request does not immediately return the results of the image generation process. Instead, the response includes an **operation-location** header with a URL for a callback service that your application code can poll until the results of the image generation are ready. The **result** element includes a collection of **url** elements, each of which references a PNG image file generated from the prompt.

[Use the Azure OpenAI REST API to consume DALL-E models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/generate-images-azure-openai/4-dall-e-rest-api)

========== Id ==========  
194

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#194-You-are-creating-an-application-that-refer

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
