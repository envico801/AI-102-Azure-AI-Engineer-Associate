========== Question ==========  

### You have an app named App1 that extracts invoice data from PDF files by using an S0 instance of Azure AI Document Intelligence. The PDF files are up to 2 MB each and contain up to 10 pages.

Users report that App1 is unable to process some invoices.

You need to troubleshoot the issue.

What is a possible cause of the issue?

Select only one answer.

-   Some of the files are password protected.

-   Some of the files are too large.

-   Some of the files have too many pages.

-   The tier of the Azure AI Document Intelligence instance is insufficient.  

========== Answer ==========  

---

###### 1. Some of the files are password protected.

The service cannot process password-protected files, and this can cause the service a processing failure for some of the files. Although file size and number of pages can cause failures, the limit for the S0 tier is 500 MB and 2,000 pages.

The S0 tier is sufficient for the file characteristics mentioned.

[Invoice data extraction – Form Recognizer - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/form-recognizer/concept-invoice?view=form-recog-3.0.0)

[Extract data from forms with Form Recognizer - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/work-form-recognizer/)

========== Id ==========  
215

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#215-You-have-an-app-named-app1-that-extracts-i

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
