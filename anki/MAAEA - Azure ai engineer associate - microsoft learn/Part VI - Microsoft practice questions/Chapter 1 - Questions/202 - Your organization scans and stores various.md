========== Question ==========  

### Your organization scans and stores various document types, such as invoices, receipts, and custom forms, in PDF format.

You need to extract structured information from these documents for analysis.

Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

-   Convert the documents into plain text.

-   Train a custom model using labeled datasets in Azure AI Document Intelligence.

-   Use the General Document model in Azure AI Document Intelligence.

-   Use the Layout model in Azure AI Document Intelligence.

-   Use the prebuilt Invoice model in Azure AI Document Intelligence.  

========== Answer ==========  

---

###### 1. Train a custom model using labeled datasets in Azure AI Document Intelligence.

###### 2. Use the prebuilt Invoice model in Azure AI Document Intelligence.

Converting the documents into plain text results in the loss of structural information, which is essential for extracting meaningful data. Training a custom model using labeled datasets in Azure AI Document Intelligence enables accurate extraction of data from unique forms that do not conform to standard templates. The General Document model is deprecated and not recommended for use in new solutions, making it unsuitable for this task. The Layout model can extract text and structure but is not optimized for specific document types like invoices or receipts, which limits its effectiveness for this scenario. The prebuilt Invoice model in Azure AI Document Intelligence is specifically designed to extract key information from invoices, making it an appropriate choice for this task.

[Get started with Azure Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)

[Choose a model type - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/4-choose-model-type)

========== Id ==========  
202

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#202-Your-organization-scans-and-stores-various

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
