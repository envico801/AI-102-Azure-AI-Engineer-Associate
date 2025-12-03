========== Question ==========  

### You have an Azure OpenAI in Foundry Models solution. The solution uses a specific GPT-35-Turbo model version that was current during initial deployment. Auto-update is disabled.

Sometime later, you investigate the deployed solution and discover that it uses a newer version of the model.

Why was the model version updated?

Select only one answer.

-   Auto-update is always enabled.

-   Auto-update is enabled automatically when a new version is released.

-   Model versions are updated automatically when the version is older than five version updates.

-   The model version reached its retirement date.  

========== Answer ==========  

---

###### 1. The model version reached its retirement date.

As your use of Azure OpenAI evolves, and you start to build and integrate with applications, you might want to manually control model updates so that you can first test and validate whether model performance remains consistent for a use case before performing an upgrade.

When you select a specific model version for a deployment, this version will remain selected until you either choose to manually update it, or once you reach the retirement date of the model. When the retirement date is reached, the model will upgrade to the default version automatically at the time of retirement.

[Azure OpenAI Service working with models - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/how-to/working-with-models?tabs=powershell)

========== Id ==========  
193

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#193-You-have-an-azure-openai-in-foundry-models

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
