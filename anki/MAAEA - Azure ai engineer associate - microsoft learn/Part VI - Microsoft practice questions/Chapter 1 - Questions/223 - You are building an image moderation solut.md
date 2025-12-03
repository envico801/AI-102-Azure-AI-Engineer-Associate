========== Question ==========  

### You are building an image moderation solution based on Azure AI Foundry Content Safety.

You migrate images to an Azure Blob Storage location.

You need to configure an access solution to enable the Foundry Content Safety solution to analyze the images.

Which two actions should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

-   Assign the Storage Blob Data Contributor/Owner/Reader role to the user-assigned managed identity.

-   Assign the Storage Blob Data Contributor/Owner/Reader role to the system-assigned managed identity.

-   Enable a system-assigned managed identity for the Content Safety instance.

-   Enable a user-assigned managed identity for the Content Safety instance.  

========== Answer ==========  

---

###### 1. Assign the Storage Blob Data Contributor/Owner/Reader role to the system-assigned managed identity.

###### 2. Enable a system-assigned managed identity for the Content Safety instance.

The only way to provide a Content Safety resource with access to images in Azure Blog Storage, is to enable a system-assigned managed identity and to assign the role Storage Blob Data Contributor/Owner/Reader to that managed identity. User-assigned managed identities are not permitted in that scenario.

[Quickstart: Analyze image content - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-image?tabs=visual-studio%2Cwindows&pivots=programming-language-rest)

========== Id ==========  
223

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#223-You-are-building-an-image-moderation-solut

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
