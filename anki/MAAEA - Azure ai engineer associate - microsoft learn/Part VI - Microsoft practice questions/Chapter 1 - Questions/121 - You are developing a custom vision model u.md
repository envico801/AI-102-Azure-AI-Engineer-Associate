========== Question ==========  

### You are developing a custom vision model using Microsoft Azure Custom Vision to classify images of various food items. The dataset includes images labeled as 'vegetable-fruit', 'dessert', and 'soup'.

You need to optimize the training process to improve the model's performance metrics.

Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

-   Select the 'Food' domain.

-   Select the 'General' domain.

-   Set a high probability threshold during training.

-   Use consistent tags to label images.  

========== Answer ==========  

---

###### 1. Select the 'Food' domain.

###### 2. Use consistent tags to label images.

Using consistent tags to label images ensures that the model can accurately associate visual features with their respective categories, which is essential for effective training. Selecting the 'Food' domain optimizes the model for food-related image classification tasks, leveraging domain-specific features to enhance performance. Setting a high probability threshold during training is not suitable because it could reduce recall by limiting the number of classifications detected. Similarly, selecting the 'General' domain is not ideal as it lacks the specialization required for food-related tasks, potentially leading to suboptimal results.

[Understand types of classification projects - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/custom-text-classification/2-understand-types-of-classification-projects)

[Select a domain for a Custom Vision project - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/select-domain)

========== Id ==========  
121

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#121-You-are-developing-a-custom-vision-model-u

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
