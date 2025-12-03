========== Question ==========  

### Your organization processes sensitive documents, such as contracts and invoices, and must comply with data privacy regulations.

You need to use Microsoft Azure AI Document Intelligence to automate structured data extraction from these documents.

Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

-   Configure an Azure AI Search resource.

-   Manually preprocess documents to remove sensitive information.

-   Upload documents to Azure Blob Storage.

-   Use the General Document model.

-   Use the Layout model.  

========== Answer ==========  

---

###### 1. Upload documents to Azure Blob Storage.

###### 2. Use the Layout model.

Uploading documents to Azure Blob Storage ensures that the documents are secure and accessible for processing and analysis. Using the Layout model is critical for extracting key-value pairs and entities from structured and semi-structured documents, directly addressing the requirements of the task. Manually preprocessing documents to remove sensitive information is unnecessary because Azure AI Document Intelligence can handle sensitive data without manual intervention. The General Document model is deprecated and no longer used. Configuring an Azure AI Search resource is not necessary for this task.

[Use the General Document, Read, and Layout models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/3-use-general-document-read-layout-models)

========== Id ==========  
133

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#133-Your-organization-processes-sensitive-docu

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
