========== Question ==========  

### You are creating an application that will use Azure OpenAI REST API services. The application uses a REST call to a DALL-E model to generate images. The three parameters in the REST call are `prompt`, `n`, and `size`.

What does the `size` parameter indicate?

Select only one answer.

-   the number of responses that you want returned

-   the size of the images in bytes

-   the size of the images in kilobytes

-   the size of the images in pixel resolution  

========== Answer ==========  

---

###### 1. the size of the images in pixel resolution

To make a REST call to the services, you need the endpoint and authorization key for the Azure OpenAI service resource you provisioned in Azure. You initiate the image generation process by submitting a `POST` request to the service endpoint that has the authorization key in the header. The request must contain the following parameters in a JSON body:

-   `prompt`: The description of the image to be generated

-   `n`: The number of images to be generated

-   `size`: The resolution of the image to be generated (_256x256_, _512x512_, or _1024x1024_)

[Use the Azure OpenAI REST API to consume DALL-E models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/generate-images-azure-openai/4-dall-e-rest-api)

========== Id ==========  
142

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#142-You-are-creating-an-application-that-will

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
