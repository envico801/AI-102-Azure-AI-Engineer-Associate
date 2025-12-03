========== Question ==========  

### You have an app named App1 that analyzes social media mentions and determines whether comments are positive or negative.

During testing, you notice that App1 generates negative sentiment analysis in response to customer feedback that contains positive feedback.

You need to ensure that App1 includes more granular information during the analysis.

What should you add to the API requests?

Select only one answer.

-   `loggingOptOut=true`

-   `StringIndexType=TextElements_v8`

-   `opinionMining=true`  

========== Answer ==========  

---

###### 1. `opinionMining=true`

`opinionMining=true` will add aspect-based sentiment analysis, which in turn will make the sentiment more granular so that positive and negative in a single sentence can be returned.

`loggingOptOut=true` will opt out of logging and `StringIndexType=TextElements_v8` will set the returned offset and length values to correspond with `TextElements`.

[Text Analysis Runtime - Analyze Text - REST API (Azure Cognitive Services - Language) | Microsoft Learn](https://learn.microsoft.com/rest/api/language/text-analysis-runtime/analyze-text?view=rest-language-2023-04-01&tabs=HTTP)

[How to perform sentiment analysis and opinion mining - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/sentiment-opinion-mining/how-to/call-api)

[Extract insights from text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

========== Id ==========  
211

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#211-You-have-an-app-named-app1-that-analyzes-s

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
