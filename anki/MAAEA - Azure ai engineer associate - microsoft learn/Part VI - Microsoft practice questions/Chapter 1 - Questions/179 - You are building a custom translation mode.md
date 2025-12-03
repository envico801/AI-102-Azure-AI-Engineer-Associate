========== Question ==========  

### You are building a custom translation model.

You need to use bilingual training documents to teach the model your terminology and style.

Which rule should you follow?

Select only one answer.

-   Be liberal.

-   Be restrictive.

-   Be strict.  

========== Answer ==========  

---

###### 1. Be liberal.

Be liberal is correct. Any in-domain human translation is better than machine translation. Add and remove documents as you go and try to improve the Bilingual Evaluation Understudy (BLEU) score.

Be strict is incorrect. Compose them to be optimally representative of what you are going to translate in the future. Be restrictive is also incorrect. A phrase dictionary is case-sensitive, and any word or phrase listed is translated in the way you specify. In many cases, it is better to not use a phrase dictionary and let the system learn.

[Custom Translator for beginners - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/custom-translator/beginners-guide#what-should-i-use-for-training-material)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

========== Id ==========  
179

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#179-You-are-building-a-custom-translation-mode

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
