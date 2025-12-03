========== Question ==========  

### Your organization processes a large volume of scanned vendor documents, some of which are poorly scanned or contain creases.

You need to extract structured data such as vendor details, totals, and line items from these invoices.

What should you use to achieve this goal?

Select only one answer.

-   Train a custom model in Azure AI Document Intelligence Studio.

-   Use Azure AI Vision OCR.

-   Use the Invoice model in Azure AI Document Intelligence.

-   Use the Business Card model in Azure AI Document Intelligence.  

========== Answer ==========  

---

###### 1. Use the Invoice model in Azure AI Document Intelligence.

The Invoice model in Azure AI Document Intelligence is the optimal choice for processing invoices due to its specialized capabilities for extracting structured data, even from poorly scanned documents. Training a custom model is unnecessary because the Invoice model already meets the requirements. Azure AI Vision OCR lacks the ability to extract structured data, making it unsuitable for this task. The Business Card model is designed for business cards and does not provide the necessary functionality for processing invoices.

[Use financial, , and tax models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/4-use-financial-id-tax-models)

========== Id ==========  
129

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#129-Your-organization-processes-a-large-volume

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
