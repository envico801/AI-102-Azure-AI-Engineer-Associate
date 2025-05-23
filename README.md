<!-- Header & Badge -->

<div align="center">
  <img src="./images/microsoft-certified-associate-badge.svg" alt="Azure AI Engineer Associate Badge" height="150" />
  <h1>AI-102: Azure AI Engineer Associate – Study Guide</h1>
  <p><em>Based on the exam objectives valid from April 30, 2025</em></p>
</div>

## 📋 Overview

This study guide is designed for developers and AI engineers preparing for the **AI-102: Azure AI Engineer Associate** certification. It covers building, managing, and deploying AI solutions using Azure AI services, including Azure AI Search, Azure OpenAI, Azure AI Studio, and more. This guide helps structure your study across planning, managing, implementing vision and NLP workloads, knowledge mining, content moderation, agentic solutions, and generative AI tasks.

## 🎯 Exam Objectives & Detailed Resources

The [AI-102 exam measures proficiency across six domains](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102#skills-at-a-glance) with the following weightings. **Click on each objective link below to find a detailed skills breakdown mapped to specific Microsoft Learn modules and relevant documentation links.**

- [Plan and manage an Azure AI solution](./plan-and-manage-an-azure-ai-solution/README.md) **(20–25%)**
- [Implement generative AI solutions](./implement-generative-ai-solutions/README.md) **(15–20%)**
- [Implement an agentic solution](./implement-an-agentic-solution/README.md) **(5–10%)**
- [Implement computer vision solutions](./implement-computer-vision-solutions/README.md) **(10–15%)**
- [Implement natural language processing solutions](./implement-natural-language-processing-solutions/README.md) **(15–20%)**
- [Implement knowledge mining and information extraction solutions](./implement-knowledge-mining-and-information-extraction-solutions/README.md) **(15–20%)**

## 💡 Exam Insights & Preparation Tips

- **Pacing:** The exam allows ample time (1 hour 40 minutes). Don't rush; take your time to read and understand each question thoroughly. The questions are generally concise.

* **Logical Thinking:** Questions often involve selecting the right sequence of actions or combining multiple Azure AI services to solve a problem. Think logically about how services would naturally work together – Microsoft designs these for practical use, not to trick you.
  - **Example:** If a question asks how to process images of book pages to make their text available in multiple languages, you'd logically think:
    1. First, I need to extract the text from the images. The `Read API (Azure AI Vision)` is suitable for extracting large amounts of printed text.
    1. Next, I need to translate that extracted text. The `Azure AI Translator` service is designed for this.

- **No Live Coding Lab:** You won't be required to write code from scratch in a lab environment during the exam.
- **Code Comprehension is Key:** The exam *will* present code snippets (you choose C# or Python at the start). You'll need to understand what the code does, identify correct functions/endpoints to call, or select appropriate code blocks.
- **Hands-on Labs are Crucial:** While not *in* the exam, completing the hands-on labs associated with the Microsoft Learn modules (like those in the [AI-102T00 Course](https://learn.microsoft.com/en-us/training/courses/ai-102t00)) is highly recommended. This practice provides the necessary experience to handle the code-related questions effectively.
- **Core Knowledge:**
  - Understand the purpose and capabilities of each Azure AI service covered in the objectives.
  - Be familiar with common REST API concepts (endpoints, methods like GET/POST, JSON request/response).
  - Know how to use the Azure SDKs (at least conceptually for your chosen language).
  - Understand endpoint naming structures (e.g., `*.cognitiveservices.azure.com`).
  - Be familiar with [Responsible AI principles](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai).
  - Basic DevOps concepts (Source Control/Git, CI/CD pipelines)
- **Utilize Official Resources:** Thoroughly review the detailed Study Guide ([Skills Measured](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102#skills-measured-as-of-april-30-2025)). These are the foundation for passing.

## 📚 Core Study Resources

These resources provide a broad overview and foundational learning:

- **Exam Page:** [Develop AI solutions with Azure AI Services](https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-102/)
- **Official Microsoft Course:** [AI-102T00: Designing and Implementing a Microsoft Azure AI Solution](https://learn.microsoft.com/en-us/training/courses/ai-102t00)
- **Key Video Resource:** [AI-102 Study Cram - Azure AI Engineer Associate Certification (YouTube)](https://www.youtube.com/watch?v=I7fdWafTcPY) - *This video serves as a helpful pillar for review, but always refer to the official Learn Path and documentation for the most current and detailed information.*
- **Official Exam Study Guide:** [AI-102 Study Guide on Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102) - *Outlines the skills measured.*
- **Azure AI Services Documentation Hub:** [Overview of Azure AI Services](https://learn.microsoft.com/en-us/azure/ai-services/) - *Essential for deep dives into specific service features, APIs, and SDKs.*
- **Exam Readiness Zone:** [AI-102 Prep Videos (Check for updated versions)](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/)
- **Azure SDK Documentation:** [Azure SDK Releases (Find Python/C# SDKs)](https://azure.github.io/azure-sdk/) - *Crucial for practical implementation tasks.*

## 🧠 Flashcards & Memory Aids

Import the provided Anki deck (`/anki/AI-102.apkg`) for spaced-repetition of key terms, definitions, and code snippets.

## 📝 Practice Questions

Test your knowledge with official practice assessments:

- **Microsoft Learn Practice Assessment:** [Official AI-102 Practice Questions](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/practice/assessment?assessment-type=practice&assessmentId=61&practice-assessment-type=certification)

## 🔬 Hands-on Labs & Projects

Apply theory with practical exercises:

- [MicrosoftLearning/AI-102-AIEngineer GitHub Repo](https://github.com/MicrosoftLearning/AI-102-AIEngineer) - *Make sure you are using the latest version aligned with the current exam objectives.*
- [madebygps/cloud-engineering-projects (AI-102 section)](https://github.com/madebygps/cloud-engineering-projects/tree/main/ai-102)
