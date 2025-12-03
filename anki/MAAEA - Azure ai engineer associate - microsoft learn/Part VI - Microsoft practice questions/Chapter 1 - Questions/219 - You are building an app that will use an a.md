========== Question ==========  

### You are building an app that will use an Azure AI Foundry Service resource.

You need to identify the endpoint for the resource.

From the Azure CLI, which command should you run?

Select only one answer.

-   `az cognitiveservices account show `

-   `az cognitiveservices account show --name myresource`

-   `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group `

-   `az cognitiveservices account show --resource-group cognitive-services-resource-group `  

========== Answer ==========  

---

###### 1. `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group `

As you need to provide the name and the resource group for your Cognitive Service account to retrieve the endpoint amongst other information for the resource, `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group` is the only valid command.

[az cognitiveservices account | Microsoft Learn](https://learn.microsoft.com/cli/azure/cognitiveservices/account?view=azure-cli-latest#az-cognitiveservices-account-show)

[Create and consume Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-manage-cognitive-services/)

========== Id ==========  
219

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#219-You-are-building-an-app-that-will-use-an-a

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
