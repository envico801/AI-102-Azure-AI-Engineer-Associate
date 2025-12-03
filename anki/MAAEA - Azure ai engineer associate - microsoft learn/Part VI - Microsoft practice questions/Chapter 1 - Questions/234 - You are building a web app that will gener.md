========== Question ==========  

### You are building a web app that will generate images based on user prompts. The app will use the DALL-E 3 Azure OpenAI model.

You need to ensure that HTTP requests against the Azure OpenAI API successfully generate images.

Which HTTP body property should you include?

Select only one answer.

-   the API version

-   the Azure OpenAI resource name

-   the deployment

-   the prompt  

========== Answer ==========  

---

###### 1. the prompt

The prompt is the only required property to be used in the body of the HTTP request when requesting to generate a new image by using the DALL-E 3 Azure OpenAI API. The other properties are used in the HTTP header.

[Azure OpenAI Service REST API reference - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/reference#image-generation)

========== Id ==========  
234

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#234-You-are-building-a-web-app-that-will-gener

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
