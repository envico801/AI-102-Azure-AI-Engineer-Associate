========== Question ==========  

### You have an app that sends audio recordings from a call center to the speech-to-text feature of Azure AI Foundry Service.

During testing, you notice that the Word Error Rate (WER) is high and there are a lot of substitution errors.

You need to improve the model and reduce the WER.

What should you add to the training data?

Select only one answer.

-   custom product and people names

-   overlapping speakers

-   people talking in the background  

========== Answer ==========  

---

###### 1. custom product and people names

Substitution errors are due to the model needing more training on custom product names and people names.

Overlapping speakers define when there are more deletion errors. People talking in the background are detected when there are more insertion errors.

[Test accuracy of a Custom Speech model - Speech service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/how-to-custom-speech-evaluate-data?pivots=speech-studio#resolve-errors-and-improve-wer)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

========== Id ==========  
240

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#240-You-have-an-app-that-sends-audio-recording

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
