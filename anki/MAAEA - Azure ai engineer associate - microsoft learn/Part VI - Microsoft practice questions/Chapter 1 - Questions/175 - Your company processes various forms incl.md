========== Question ==========  

### Your company processes various forms, including health insurance cards and identity documents, and requires accurate extraction of specific fields.

You need to recommend a solution for extracting structured data from these forms.

What should you do?

Select only one answer.

-   Train a composed model.

-   Use Azure OCR.

-   Use prebuilt models for Health Insurance Card and Document.

-   Use the Layout model.  

========== Answer ==========  

---

###### 1. Use prebuilt models for Health Insurance Card and Document.

Prebuilt models for Health Insurance Card and Document in Microsoft Azure AI Document Intelligence are the optimal choice for extracting structured data from these forms because they are specifically designed for this purpose, ensuring accuracy and efficiency. Training a composed model introduces unnecessary complexity when prebuilt models are available for these document types. Azure OCR focuses on text extraction without contextual understanding, making it unsuitable for structured data extraction. The Layout model supports key-value pair extraction but lacks the specificity required for extracting specific fields from health insurance cards and identity documents.

[Understand AI Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/2-understand)

[Get started with Azure Document Intelligence](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)

========== Id ==========  
175

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#175-Your-company-processes-various-forms-incl

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
