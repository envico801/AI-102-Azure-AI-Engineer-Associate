========== Question ==========  

### You are provisioning an Azure OpenAI in Foundry Models service resource.

You need to ensure that the resource is only available to applications that are hosted in your Azure subscription.

Which network security setting should you configure?

Select only one answer.

-   All networks

-   All networks, and a network security group to control traffic

-   Disabled, and allow a private endpoint connection to establish access

-   Selected networks  

========== Answer ==========  

---

###### 1. Disabled, and allow a private endpoint connection to establish access

Because the requirements state that access to the resource should only be for applications hosted in the Azure subscription, setting the network option to Disabled and configuring a private endpoint meets this requirement.

All networks permit access to any network, including the internet. Selected networks access to networks outside of Azure, if configured that way.

[How-to: Create and deploy an Azure OpenAI Service resource - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/how-to/create-resource?pivots=web-portal)

========== Id ==========  
140

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#140-You-are-provisioning-an-azure-openai-in-fo

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
