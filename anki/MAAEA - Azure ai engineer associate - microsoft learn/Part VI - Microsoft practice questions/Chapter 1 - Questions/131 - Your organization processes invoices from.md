========== Question ==========  

### Your organization processes invoices from vendors in various formats, including scanned PDFs and digital images.

You need to implement Azure AI Document Intelligence to extract key fields such as invoice number, due date, and total amount.

Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

-   Create a custom model for invoice processing.

-   Install the solution on a local server.

-   Label all invoice documents manually.

-   Provision an Azure AI Document Intelligence resource.

-   Edit the invoices to ensure consistency.

-   Use the prebuilt invoice model to extract key fields.  

========== Answer ==========  

---

###### 1. Provision an Azure AI Document Intelligence resource.

###### 2. Use the prebuilt invoice model to extract key fields.

To implement the solution, provisioning the Azure AI Document Intelligence resource is a necessary first step to enable its capabilities. Using the prebuilt invoice model is the most efficient approach for extracting key fields such as invoice number, due date, and total amount, as it is specifically designed for this purpose. Installing the solution on a local server is irrelevant because the service is cloud-based and does not require local installation. Creating a custom model is unnecessary because the prebuilt invoice model already meets the requirements, saving time and effort. Manually labeling invoice documents is also not needed, as the prebuilt model leverages pre-trained capabilities to eliminate this step. Editing the invoices to ensure consistency won't help when processing incoming invoices and doesn't provide the model with varied training data

[Document Intelligence invoice model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/invoice)

========== Id ==========  
131

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#131-Your-organization-processes-invoices-from

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
