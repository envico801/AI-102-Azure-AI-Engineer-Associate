========== Question ==========  

### Your company receives multi-page PDF documents from clients containing specifications and statements of work, often including tables and selection marks.

You need to extract text, tables, and selection marks while maintaining the document's structure.

What should you recommend?

Select only one answer.

-   Azure AI Vision OCR (Optical Character Recognition)

-   Azure Document Intelligence general model

-   Azure Document Intelligence layout model

-   Azure Document Intelligence read model  

========== Answer ==========  

---

###### 1. Azure Document Intelligence layout model

Azure Document Intelligence layout model is the most appropriate solution because it is specifically designed to extract text, tables, and selection marks while preserving the document's structure, which is essential for processing multi-page PDF documents. Azure AI Vision OCR is limited to text extraction from images and does not support advanced features like table or selection mark recognition. The general model supports entity extraction but does not focus on maintaining the document's structure. The read model is limited to extracting printed and handwritten text and does not include the advanced capabilities required for this scenario.

[What is Azure Document Intelligence? - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/2-what-form-recognizer)

[Use the General Document, Read, and Layout models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/3-use-general-document-read-layout-models)

========== Id ==========  
176

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#176-Your-company-receives-multi-page-pdf-docum

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
