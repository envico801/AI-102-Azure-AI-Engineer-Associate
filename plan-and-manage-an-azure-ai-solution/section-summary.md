## Plan and prepare to develop AI solutions on Azure

### [Introduction](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/1-introduction)

- **Context:** Growth in AI, especially **Generative AI**, drives the need for developers to build comprehensive AI solutions.
- **Solution Complexity:** Modern AI solutions combine ML models, AI services, prompt engineering, and custom code.
- **Azure's Role:** Microsoft Azure offers multiple services for building these solutions.
- **Importance of Planning:** Before starting, consider available services, tools, frameworks, principles, and best practices.
- **Focus:** This module introduces planning considerations and **Azure AI Foundry** as the recommended Azure platform for AI development.

______________________________________________________________________

### [What is AI?](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/2-what-is-ai)

- **Definition:** AI encompasses software with human-like behavior, built on ML **models** that understand semantic relationships in data.
- **Core Function:** Interpret input (various formats), reason over it, generate responses/predictions.
- **Common AI Capabilities:**
  - 🤖 **Generative AI:** Creates original content (text, images, code) from natural language **prompts** using **language models** (LLMs/SLMs). Can be **multi-modal**.
  - 🧑‍💼 **Agents:** Autonomous AI that responds to input or assesses situations and takes actions.
  - 👁️ **Computer Vision:** Interprets visual input (images, video, camera streams).
  - 🗣️ **Speech:** Recognizes and synthesizes spoken language.
  - ✍️ **Natural Language Processing (NLP):** Processes written/spoken language (analysis, translation, sentiment, summarization).
  - 📄 **Information Extraction:** Extracts key data from documents, images, audio etc., using other AI capabilities.
  - 📈 **Decision Support:** Uses historical data and correlations for predictions to aid decision-making.
- **Generative AI Deep Dive:** Uses large (LLM) or small (SLM) language models; responds to prompts; can be multi-modal (handle/generate text, images, speech, code).

______________________________________________________________________

### [Azure AI Services](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

- **Definition:** A suite of pre-built AI APIs and models provided by Azure.
- **Key Services Examples:**
  - **Azure OpenAI:** Access to OpenAI models (GPT family, DALL-E) in Azure.
  - **Azure AI Vision:** Image analysis (objects, captions, tags, text reading).
  - **Azure AI Speech:** Speech-to-text, text-to-speech, speaker recognition, translation.
  - **Azure AI Language:** Text analysis (entities, sentiment, summarization), conversational AI, Q&A.
  - **Azure AI Content Safety:** Detects potentially harmful/offensive text and images.
  - **Azure AI Translator:** Text translation between many languages.
  - **Azure AI Face:** Face detection, analysis, recognition (*restricted access*).
  - **Azure AI Custom Vision:** Train custom models for image classification/object detection.
  - **Azure AI Document Intelligence:** Extract data from forms/documents (pre-built/custom models).
  - **Azure AI Content Understanding:** Multi-modal analysis (forms, documents, images, video, audio).
  - **Azure AI Search:** Create searchable indexes using AI skills (often used for grounding GenAI).
- **Provisioning Considerations:**
  - **Single Service:** Provision individual services (e.g., AI Vision) - often have free tiers.
  - **Multi-Service (`Azure AI services` resource):** Bundles multiple services (OpenAI, Vision, Speech, Language, Safety, Translator, Doc Intel., Content Under.) under one endpoint/key. Simplifies management for multi-capability apps.
  - **Recommendation:** Provision via **Azure AI Foundry Hubs** for better management in larger projects.
- **Other Considerations:**
  - **Regional Availability:** Check which services/models are available in your target Azure region.
  - **Cost:** Usage-based pricing; use the pricing calculator to estimate costs.

______________________________________________________________________

### [Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

- **Definition:** Azure's **recommended comprehensive platform** for AI development (Web Portal + SDK). *(Note: Azure AI Studio is the user interface for Azure AI Foundry capabilities)*
- **Structure:**
  - **Hubs:**
    - Top-level container for **shared resources**, data, connections, security configuration across projects.
    - Centralizes management (IT admin manages access/resources).
    - Creates an **Azure AI Hub** Azure resource, plus associated **Azure AI services** (multi-service), **Key Vault**, **Storage Account**, and optional **AI Search**.
    - Manages **users** and **roles** (Owner, Contributor, AI Developer, Inference Operator, Reader).
    - Resources/connections defined here are **inherited** by associated projects.
  - **Projects:**
    - Workspace within a Hub for a **specific AI solution**.
    - Developers collaborate here.
    - Uses inherited Hub resources + can have **project-specific connected resources**.
    - Provides tools like:
      - Model Catalog (OpenAI, Hugging Face)
      - Playgrounds (prompt testing)
      - Azure AI Services access
      - VS Code containers (hosted dev environment)
      - Fine-tuning capabilities
      - **Prompt Flow** (visual prompt orchestration)
      - Evaluation & Responsible AI tools (tracing, content safety)
      - Asset management (models, endpoints, data, apps)
    - Manages access via **project-level roles** (Owner, Contributor, AI Developer, Inference Operator, Reader).
- **Planning Considerations:**
  - **Hub/Project Organization:** Plan a structure that makes sense for your teams/business areas.
  - **Connected Resources:** Decide which resources are shared (Hub level) vs. specific (Project level). Hub connections provide proxy access for project users.
  - **Roles & Permissions:** Assign appropriate Hub and Project roles.
  - **Regional Availability:** Verify needed Foundry/Studio features are in your region.
  - **Costs & Quotas:** Budget for Foundry/Studio infrastructure (compute, storage) and underlying service usage; ensure adequate quotas.

______________________________________________________________________

### [Developer Tools and SDKs](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

- **Development Environments:** Use standard tools like **Visual Studio** or **Visual Studio Code (VS Code)**.
- **Azure AI Foundry VS Code Container:**
  - A pre-configured, hosted VS Code environment accessible within the Foundry/Studio portal.
  - **Benefit:** Includes up-to-date Azure AI SDKs.
  - **Consideration:** Requires compute resources (cost/quota).
- **Source Control & Assistance:**
  - **GitHub:** Essential for team collaboration, source control, DevOps.
  - **GitHub Copilot:** AI pair programmer for increased productivity. Integrated into VS/VS Code.
- **Programming Languages:** Supports common languages (C#, Python, Node, Java, etc.).
- **Key SDKs/APIs for Azure AI:**
  - **Azure AI Foundry SDK:** Interact with Foundry projects, access connections. *(Often referred to as Azure AI SDK)*
  - **Azure AI Services SDKs:** Language-specific libraries to consume individual AI services (alternatively, use **REST APIs**).
  - **Azure AI Agent Service SDK:** Build AI agents (integrates with frameworks like **AutoGen**, **Semantic Kernel**). Accessed via Foundry SDK.
  - **Prompt Flow SDK:** Programmatically define and manage prompt orchestration flows.

______________________________________________________________________

### [Responsible AI](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai)

- **Importance:** Critical for developers to consider the societal impact and ethical use of AI due to its nature (probabilistic, data-dependent, potential for bias/harm).
- **Microsoft's 6 Core Principles:**
  1. ⚖️ **Fairness:** Treat all people fairly, avoid bias (gender, ethnicity, etc.). Requires careful data review and evaluation across subgroups.
  1. 🛡️ **Reliability & Safety:** Perform reliably and safely, especially in high-risk systems. Rigorous testing is essential.
  1. 🔒 **Privacy & Security:** Protect user data and system integrity. Secure handling of training and production data.
  1. 🤝 **Inclusiveness:** Empower everyone and benefit all parts of society. Involve diverse perspectives in development.
  1. 👁️ **Transparency:** AI systems should be understandable. Users should know the purpose, limitations, and how data is used.
  1. 📜 **Accountability:** Humans are ultimately responsible. Develop within governance frameworks ensuring legal/ethical compliance.
