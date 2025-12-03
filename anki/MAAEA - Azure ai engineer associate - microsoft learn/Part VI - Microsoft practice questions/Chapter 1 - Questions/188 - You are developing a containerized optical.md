========== Question ==========  

### You are developing a containerized optical character recognition (OCR)-capable application by using Azure AI Services containers.

While developing the solution, you retrieve a status message of “Mismatch”, and the connection to the AI Services resource fails.

You need to ensure that the solution can connect to the AI Services resource.

What should you do?

Select only one answer.

-   Confirm that the API key is for the correct region.

-   Confirm that the API key is for the correct resource type.

-   Confirm that the Azure AI Services resource is online.

-   Upgrade the Azure AI Services resource to a higher tier.  

========== Answer ==========  

---

###### 1. Confirm that the API key is for the correct resource type.

Mismatch means that the wrong API key has been used. If you have provided an API key or endpoint for a different kind of Azure AI Services resource, you find your API key and service region in the Azure portal, in the Keys and Endpoint section for your Azure AI Services resource.

If the API key is invalid, you must confirm that the API key is for the correct region. If the API key has exceeded the quota, then you can either upgrade your pricing tier or wait for an additional quota to become available. Find your tier in the Azure portal, in the Pricing Tier section of your Azure AI Service resource. The mismatch error would not be generated if the resource was offline.

[Cognitive Services containers FAQ - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/containers/container-faq)

[Deploy cognitive services in containers - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/investigate-container-for-use-cognitive-services/)

========== Id ==========  
188

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#188-You-are-developing-a-containerized-optical

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
