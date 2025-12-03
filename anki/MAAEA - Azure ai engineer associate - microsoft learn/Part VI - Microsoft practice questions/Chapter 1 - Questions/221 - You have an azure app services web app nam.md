========== Question ==========  

### You have an Azure App Services web app named App1.

You need to configure App1 to use Azure AI Services to authenticate by using Microsoft Entra . The solution must meet the following requirements:

-   Minimize administrative effort.

-   Use the principle of least privilege.

What should you do?

Select only one answer.

-   Create a secret and store the secret in an Azure key vault. Assign App1 role-based access control (RBAC) permissions to the secret.

-   Create a Microsoft Entra app registration and enable certificate-based authentication.

-   From App1, enable a managed identity and assign role-based access control (RBAC) permissions to Azure AI Services.

-   From PowerShell, create a secret that never expires.  

========== Answer ==========  

---

###### 1. From App1, enable a managed identity and assign role-based access control (RBAC) permissions to Azure AI Services.

With a managed identity, the rotation of the secrets (certificates) is done automatically.

You still need to rotate secrets by using the key vault, and you cannot create secrets that never expire from the portal. It is not considered best practice to create one with PS1 or the CLI, and a certificate will also expire at some point.

[Authentication in Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/authentication?tabs=powershell#authorize-access-to-managed-identities)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

========== Id ==========  
221

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#221-You-have-an-azure-app-services-web-app-nam

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
