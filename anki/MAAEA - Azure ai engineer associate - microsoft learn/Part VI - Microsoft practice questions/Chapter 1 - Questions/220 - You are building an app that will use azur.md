========== Question ==========  

### You are building an app that will use Azure AI Custom Vision. The app will be deployed to a virtual machine in Azure.

You enable firewall rules for your Azure AI Services account.

You need to ensure that the app can access the service through a service endpoint.

What should you do?

Select only one answer.

-   Assign a role-based access control (RBAC) role to the Azure AI Custom Vision resource.

-   Grant access to a specific virtual network.

-   Grant access to an internet IP range.

-   Include an access token in the Authorization header.  

========== Answer ==========  

---

###### 1. Grant access to a specific virtual network.

If you enable the firewall for the Azure AI Services account, you need to allow network access to the service. You can achieve this by either allowing access from a specific virtual network or adding an IP range to the firewall rules. In this situation, the app is deployed to a virtual machine in Azure, which resides in a virtual network. You can provide access to virtual networks in Azure to access specific service endpoints.

[Configure Virtual Networks for Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/cognitive-services-virtual-networks?context=%2Fazure%2Fcognitive-services%2Fcustom-vision-service%2Fcontext%2Fcontext&tabs=portal)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

========== Id ==========  
220

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn::Part VI - Microsoft practice questions::Chapter 1 - Questions

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102::#MAAEA-Azure-ai-engineer-associate-microsoft-learn::#Part-VI-Microsoft-practice-questions::#Chapter-1-Questions::#220-You-are-building-an-app-that-will-use-azur

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```

QUESTION STATUS: Safe to store
