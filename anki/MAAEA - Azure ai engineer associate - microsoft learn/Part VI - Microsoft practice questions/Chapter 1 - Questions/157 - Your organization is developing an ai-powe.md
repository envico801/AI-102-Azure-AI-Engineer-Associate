========== Question ==========  

### Your organization is developing an AI-powered e-learning platform that generates personalized educational content based on user inputs and reference documents. Concerns exist about generating inappropriate or misleading educational materials.

You need to ensure AI-generated educational content complies with academic standards and avoids inappropriate material.

What should you implement to address these concerns?

Select only one answer.

-   Enable Azure Translator.

-   Implement Azure AI Foundry Content Safety.

-   Train a custom model with additional datasets.

-   Use Azure AI Services Text Analytics.  

========== Answer ==========  

---

###### 1. Implement Azure AI Foundry Content Safety.

Azure Content Safety is the most suitable solution because it analyzes user inputs and reference documents to detect and block harmful or policy-violating content, ensuring generated educational materials are safe and compliant. Azure AI Services Text Analytics evaluates sentiment but does not address content safety or compliance. Training a custom model improves content relevance but does not safeguard against inappropriate or misleading outputs. Azure Translator enhances accessibility through multilingual support but does not address the core issue of ensuring content safety and compliance.

[What is Content Safety - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/responsible-content-safety/2-what-is-content-safety)

========== Id ==========  
157

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#157-Your-organization-is-developing-an-ai-powe

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
