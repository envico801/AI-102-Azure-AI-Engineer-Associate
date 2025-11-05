# MAAEA - Azure ai engineer associate - microsoft learn

## Questions

### Part I - Develop generative AI apps in Azure

#### Chapter 1 - Plan and prepare to develop AI solutions on Azure

Q:: =============================================

Which Azure resource prov
es language and vision services from a single endpoint?
- Azure AI Language
- Azure AI Vision
- Azure AI Services

A:: =============================================

Azure AI Services

Source: [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

Q:: =============================================

You plan to create a simple chat app that uses a generative AI model. What kind of project should you create?
- Azure AI Foundry project.
- Azure AI hub based project.
- Azure AI Custom Vision project.

A:: =============================================

Azure AI Foundry project.

Source: [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

Q:: =============================================

Which SDK enables you to connect to resources in a project?
- Azure AI Services SDK
- Semantic Kernel SDK
- Azure AI Foundry SDK

A:: =============================================

Azure AI Foundry SDK

Source: [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

#### Chapter 2 - Choose and deploy models from the model catalog in Azure AI Foundry portal

Q:: =============================================

Where can you test a deployed model in the Azure AI Foundry portal?
- Chat playground
- Sandbox
- Development toolbox

A:: =============================================

Chat playground

Source: [Choose and deploy models from the model catalog in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/)

Q:: =============================================

You want to specify the tone, format, and content for each interaction with your model in the playground. What should you use to customize the model response?
- Benchmarks
- Grounding
- System message

A:: =============================================

System message

Source: [Choose and deploy models from the model catalog in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/)

Q:: =============================================

What deployment option should you choose to host an OpenAI model in an Azure AI Foundry resource?
- Standard deployment
- Serverless compute
- Managed compute

A:: =============================================

Standard deployment

Source: [Choose and deploy models from the model catalog in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/)

#### Chapter 3 - Develop an AI app with the Azure AI Foundry SDK

Q:: =============================================

What class in the Azure AI Foundry SDK prov
es a proxy object for a project?
- ConnectionProperties
- AIProjectClient
- ChatCompletionsClient

A:: =============================================

AIProjectClient

Source: [Develop an AI app with the Azure AI Foundry SDK](https://learn.microsoft.com/en-us/training/modules/ai-foundry-sdk/)

Q:: =============================================

What value is needed to instantiate a AIProjectClient object?
- The project endpoint.
- The Azure OpenAI authorization key
- The Azure subscription 

A:: =============================================

The project endpoint.

Source: [Develop an AI app with the Azure AI Foundry SDK](https://learn.microsoft.com/en-us/training/modules/ai-foundry-sdk/)

Q:: =============================================

Which SDK should you use to chat with a model that is deployed in an Azure AI Foundry resource?
- Azure OpenAI
- Azure Machine Learning
- Azure AI Language

A:: =============================================

Azure OpenAI

Source: [Develop an AI app with the Azure AI Foundry SDK](https://learn.microsoft.com/en-us/training/modules/ai-foundry-sdk/)

#### Chapter 4 - Get started with prompt flow to develop language model apps in the Azure AI Foundry

Q:: =============================================

A flow uses an LLM tool to generate text with a GPT-3.5 model. What do you need to create to ensure prompt flow can securely call the deployed model from Azure OpenAI?
- Runtimes
- Connections
- Tools

A:: =============================================

Connections

Source: [Get started with prompt flow to develop language model apps in the Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/get-started-prompt-flow-ai-studio/)

Q:: =============================================

You want to integrate your flow with an online website. What do you need to do to easily integrate your flow?
- Create a custom environment.
- Create a runtime.
- Deploy your flow to an endpoint.

A:: =============================================

Deploy your flow to an endpoint.

Source: [Get started with prompt flow to develop language model apps in the Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/get-started-prompt-flow-ai-studio/)

Q:: =============================================

After deployment, you notice that your flow is underperforming. Which stage in the development lifecycle should you revert back to?
- Experimentation
- Evaluation and refinement
- Production

A:: =============================================

Experimentation

Source: [Get started with prompt flow to develop language model apps in the Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/get-started-prompt-flow-ai-studio/)

#### Chapter 5 - Develop a RAG-based solution with your own data using Azure AI Foundry

Q:: =============================================

What does groundedness refer to in the context of generative AI?
- The use of a locally deployed language model.
- Using data to contextualize prompts and ensure relevant responses.
- Using the lowest possible number of tokens in a prompt.

A:: =============================================

Using data to contextualize prompts and ensure relevant responses.

Source: [Develop a RAG-based solution with your own data using Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/)

Q:: =============================================

What pattern can you use to ground prompts?
- Metadata Optimized Prompt (MOP).
- Data Understanding Support Text (DUST).
- Retrieval Augmented Generation (RAG).

A:: =============================================

Retrieval Augmented Generation (RAG).

Source: [Develop a RAG-based solution with your own data using Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/)

Q:: =============================================

How can you use the RAG pattern in a client app that uses the Azure OpenAI SDK?
- Add text files containing the grounding data to the app folder.
- You don't need to do anything. Azure AI Foundry automatically grounds all prompts using Bing Search.
- Add index connection details to the OpenAI ChatClient configuration.

A:: =============================================

Add index connection details to the OpenAI ChatClient configuration.

Source: [Develop a RAG-based solution with your own data using Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/)

#### Chapter 6 - Fine-tune a language model with Azure AI Foundry

Q:: =============================================

How must data be formatted for fine-tuning?
- JSONL
- YAML
- HTML

A:: =============================================

JSONL

Source: [Fine-tune a language model with Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/finetune-model-copilot-ai-studio/)

Q:: =============================================

What does fine-tuning optimize in your model?
- What the model needs to know.
- How the model needs to act.
- Which words aren't allowed.

A:: =============================================

How the model needs to act.

Source: [Fine-tune a language model with Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/finetune-model-copilot-ai-studio/)

Q:: =============================================

Which advanced option refers to one full cycle through the training dataset?
- seed
- batch_size
- n_epochs

A:: =============================================

n_epochs

Source: [Fine-tune a language model with Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/finetune-model-copilot-ai-studio/)

#### Chapter 7 - Implement a responsible generative AI solution in Azure AI Foundry

Q:: =============================================

Why should you cons
er creating an AI Impact Assessment when designing a generative AI solution?
- To make a legal case that indemnifies you from responsibility for harms caused by the solution
- To document the purpose, expected use, and potential harms for the solution
- To evaluate the cost of cloud services required to implement your solution

A:: =============================================

To document the purpose, expected use, and potential harms for the solution

Source: [Implement a responsible generative AI solution in Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/)

Q:: =============================================

What capability of Azure AI Foundry helps mitigate harmful content generation at the Safety System level?
- DALL-E model support
- Fine-tuning
- Content filters

A:: =============================================

Content filters

Source: [Implement a responsible generative AI solution in Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/)

Q:: =============================================

Why should you cons
er a phased delivery plan for your generative AI solution?
- To enable you to gather feedback and 
entify issues before releasing the solution more broadly
- To eliminate the need to map, measure, mitigate, and manage potential harms
- To enable you to charge more for the solution

A:: =============================================

To enable you to gather feedback and 
entify issues before releasing the solution more broadly

Source: [Implement a responsible generative AI solution in Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/)

#### Chapter 8 - Evaluate generative AI performance in Azure AI Foundry portal

Q:: =============================================

Which evaluation technique can you use to apply your own judgement about the quality of responses to a set of specific prompts?
- Model benchmarks
- Manual evaluations
- Automated evaluations

A:: =============================================

Manual evaluations

Source: [Evaluate generative AI performance in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/evaluate-models-azure-ai-studio/)

Q:: =============================================

Which evaluator compares generated responses to ground truth based on standard metrics?
- Coherence
- F1 Score
- Protected material

A:: =============================================

F1 Score

Source: [Evaluate generative AI performance in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/evaluate-models-azure-ai-studio/)

Q:: =============================================

Which evaluator metric uses an AI model to judge the structure and logical flow of 
eas in a response?
- Coherence
- F1 Score
- protected material

A:: =============================================

Coherence

Source: [Evaluate generative AI performance in Azure AI Foundry portal](https://learn.microsoft.com/en-us/training/modules/evaluate-models-azure-ai-studio/)

### Part II - Develop AI agents on Azure

#### Chapter 1 - Get started with AI agent development on Azure

Q:: =============================================

Which of the following best describes an AI agent?
- A developer who specializes in building generative AI solutions.
- A software service that uses AI to assist users with information and task automation.
- A marketplace for off-the-shelf AI software components.

A:: =============================================

A software service that uses AI to assist users with information and task automation.

Source: [Get started with AI agent development on Azure](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

Q:: =============================================

Which AI agent development service offers a choice of generative AI models from multiple vendors in the Azure AI Foundry model catalog?
- Azure AI Foundry Agent Service
- OpenAI Assistants API
- Microsoft 365 Copilot Chat

A:: =============================================

Azure AI Foundry Agent Service

Source: [Get started with AI agent development on Azure](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

Q:: =============================================

What element of an Foundry Agent Service agent enables it to ground prompts with contextual data?
- Model
- Code interpreter tool
- Knowledge

A:: =============================================

Knowledge

Source: [Get started with AI agent development on Azure](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

#### Chapter 2 - Develop an AI agent with Azure AI Foundry Agent Service

Q:: =============================================

What is the first step in setting up Azure AI Foundry Agent Service?
- Deploy a compatible model
- Create an Azure AI Foundry project
- Make API calls using SDKs

A:: =============================================

Create an Azure AI Foundry project

Source: [Develop an AI agent with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-azure/)

Q:: =============================================

Which element of an agent definition is used to specify its behavior and restrictions?
- Model
- Instructions
- Tools

A:: =============================================

Instructions

Source: [Develop an AI agent with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-azure/)

Q:: =============================================

Which tool should you use to enable an agent to dynamically generate code to perform tasks or access data in files?
- Code Interpreter
- Azure Functions
- Azure AI Search

A:: =============================================

Code Interpreter

Source: [Develop an AI agent with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-azure/)

#### Chapter 3 - Develop AI agents with the Azure AI Foundry extension in Visual Studio Code

Q:: =============================================

When you create a new agent in the Azure AI Foundry extension, what two views are automatically opened?
- The YAML file and the Playground view
- The YAML file and the Designer view
- The Designer view and the Code Generation view

A:: =============================================

The YAML file and the Designer view

Source: [Develop AI agents with the Azure AI Foundry extension in Visual Studio Code](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-vs-code/)

Q:: =============================================

What is a key benefit of using Model Context Protocol (MCP) servers for agent tools?
- They only work with Microsoft-built tools
- They prov
e reusable components that work across different agents
- They replace the need for all built-in tools

A:: =============================================

They prov
e reusable components that work across different agents

Source: [Develop AI agents with the Azure AI Foundry extension in Visual Studio Code](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-vs-code/)

Q:: =============================================

How does the Azure AI Foundry Agent Service manage conversation sessions when users interact with deployed agents?
- The system creates indiv
ual threads for each conversation to manage context and message history
- Each message is processed independently with no conversation history
- All user conversations are combined into one shared global session

A:: =============================================

The system creates indiv
ual threads for each conversation to manage context and message history

Source: [Develop AI agents with the Azure AI Foundry extension in Visual Studio Code](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-vs-code/)

#### Chapter 4 - Integrate custom tools into your agent

Q:: =============================================

What are custom tools, and how can they help you develop effective agents with Azure AI Foundry Agent Service?
- Callable functions that an agent can use to extend its capabilities.
- Extensions for Visual Studio Code that make it easier to create and deploy agents.
- Fine-tuned models that the agent can use to generate custom output.

A:: =============================================

Callable functions that an agent can use to extend its capabilities.

Source: [Integrate custom tools into your agent](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/)

Q:: =============================================

You need to integrate functionality from an OpenAPI 3.0-based web service into an agent solution. What should you do?
- Add the JSON schema of the web service to the agent's instructions.
- Rewrite the web service as a Python function and hard-code it in your agent app.
- Add the web service as an OpenAPI specification tool to the agent definition

A:: =============================================

Add the web service as an OpenAPI specification tool to the agent definition

Source: [Integrate custom tools into your agent](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/)

Q:: =============================================

Your agent application code includes a local function that you want the agent to call. What kind of tool should you add to the agent's definition?
- Function calling
- Code interpreter
- Azure Functions

A:: =============================================

Function calling

Source: [Integrate custom tools into your agent](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/)

#### Chapter 5 - Develop a multi-agent solution with Azure AI Foundry Agent Service

Q:: =============================================

What is the role of the main agent in a connected agent system?
- To directly perform all tasks using tools
- To coordinate user input and route tasks to the appropriate connected agents
- To monitor agent performance and generate logs

A:: =============================================

To coordinate user input and route tasks to the appropriate connected agents

Source: [Develop a multi-agent solution with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-multi-agent-azure-ai-foundry/)

Q:: =============================================

How do you connect an agent to a main agent using the Azure AI Projects client library?
- Add the agent as a ConnectedAgentTool to the main agent's tool definition.
- Use the link_agents() method to bind the sub-agent to the main agent.
- Set the main agent's parent_
to the sub-agent's agent 
.

A:: =============================================

Add the agent as a ConnectedAgentTool to the main agent's tool definition.

Source: [Develop a multi-agent solution with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-multi-agent-azure-ai-foundry/)

Q:: =============================================

How does the main agent dec
e which connected agent to use?
- It uses prompt instructions and natural language understanding.
- It follows a fixed code-based decision tree.
- It randomly selects from available connected agents.

A:: =============================================

It uses prompt instructions and natural language understanding.

Source: [Develop a multi-agent solution with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-us/training/modules/develop-multi-agent-azure-ai-foundry/)

#### Chapter 6 - Integrate MCP Tools with Azure AI Agents

Q:: =============================================

What role does the MCP server play in the MCP agent tool integration?
- Runs the AI agent and processes user prompts directly.
- Manages network connections between multiple agents.
- Hosts tool definitions and makes them available for discovery by the client.

A:: =============================================

Hosts tool definitions and makes them available for discovery by the client.

Source: [Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/)

Q:: =============================================

How does an MCP client retrieve available tools from the MCP server?
- By calling session.list_tools() to get the current tool catalog.
- By reading a static JSON file from the server directory.
- By subscribing to server events via a WebSocket connection.

A:: =============================================

By calling session.list_tools() to get the current tool catalog.

Source: [Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/)

Q:: =============================================

Why should MCP tools be wrapped in async functions on the client-s
e?
- To allow the agent to wait for user input.
- To enable asynchronous invocation so the agent can call tools without blocking.
- To convert the functions into REST API endpoints automatically.

A:: =============================================

To enable asynchronous invocation so the agent can call tools without blocking.

Source: [Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/)

#### Chapter 7 - Develop an AI agent with Microsoft Agent Framework

Q:: =============================================

What are the key steps to create an Azure AI Foundry Agent using the Microsoft Agent Framework?
- Deploy a custom AI model before creating an agent definition in the Azure portal.
- Initialize the agent by defining a model in the AgentThread constructor.
- Create an AzureAIAgentClient, define a ChatAgent with instructions and tools, and create an AgentThread for conversations.

A:: =============================================

Create an AzureAIAgentClient, define a ChatAgent with instructions and tools, and create an AgentThread for conversations.

Source: [Develop an AI agent with Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/)

Q:: =============================================

Which component in the Microsoft Agent Framework manages conversation state and stores messages?
- AgentThread
- ChatAgent
- AzureAIAgentClient

A:: =============================================

AgentThread

Source: [Develop an AI agent with Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/)

Q:: =============================================

How do you add custom functionality to an Azure AI Foundry Agent in the Microsoft Agent Framework?
- Configure custom functions in the Azure portal and link them to the agent through connection strings.
- Create Python functions with proper type annotations and descriptions, then pass them to the ChatAgent's tools parameter.
- Modify the AI model's architecture to integrate the custom functionality directly.

A:: =============================================

Create Python functions with proper type annotations and descriptions, then pass them to the ChatAgent's tools parameter.

Source: [Develop an AI agent with Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/)

#### Chapter 8 - Orchestrate a multi-agent solution using the Microsoft Agent Framework

Q:: =============================================

What's the first step in the Microsoft Agent Framework's unified orchestration workflow?
- Select and create an orchestration pattern
- Define your agents and describe their capabilities
- Start a runtime to manage execution

A:: =============================================

Define your agents and describe their capabilities

Source: [Orchestrate a multi-agent solution using the Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/)

Q:: =============================================

For brainstorming and collaborative problem solving among multiple agents, which orchestration pattern is most suitable?
- Group Chat
- Magentic
- Sequential

A:: =============================================

Group Chat

Source: [Orchestrate a multi-agent solution using the Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/)

Q:: =============================================

Which pattern dynamically transfers control between agents based on context or rules?
- Handoff
- Concurrent
- Sequential

A:: =============================================

Handoff

Source: [Orchestrate a multi-agent solution using the Microsoft Agent Framework](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/)

#### Chapter 9 - Discover Azure AI Agents with A2A

Q:: =============================================

What is the primary role of an A2A server?
- It executes business logic for the agent directly.
- It routes requests between clients and connected agents.
- It stores static agent responses for reuse.

A:: =============================================

It routes requests between clients and connected agents.

Source: [Discover Azure AI Agents with A2A](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/)

Q:: =============================================

What does the Agent Executor do in an A2A agent?
- Manages network connections between clients and servers.
- Processes incoming requests and generates responses or events.
- Prov
es a GUI for monitoring agent activity.

A:: =============================================

Processes incoming requests and generates responses or events.

Source: [Discover Azure AI Agents with A2A](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/)

Q:: =============================================

What is an agent card used for in A2A?
- It stores the agent's API key for authentication.
- It prov
es metadata about the agent, such as its capabilities and available functions.
- It visualizes the agent's workflow in a GUI dashboard.

A:: =============================================

It prov
es metadata about the agent, such as its capabilities and available functions.

Source: [Discover Azure AI Agents with A2A](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/)

### Part III - Develop natural language solutions in Azure

#### Chapter 1 - Analyze text with Azure AI Language

Q:: =============================================

How should you create an application that monitors the comments on your company's web site and flags any negative posts?
- Use the Azure AI Language service to extract key phrases.
- Use the Azure AI Language service to perform sentiment analysis of the comments.
- Use the Azure AI Language service to extract named entities from the comments.

A:: =============================================

Use the Azure AI Language service to perform sentiment analysis of the comments.

Source: [Analyze text with Azure AI Language](https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/)

Q:: =============================================

You are analyzing text that contains the word "Paris". How might you determine if this word refers to the French city or the character in Homer's "The Iliad"?
- Use the Azure AI Language service to extract key phrases.
- Use the Azure AI Language service to detect the language of the text.
- Use the Azure AI Language service to extract linked entities.

A:: =============================================

Use the Azure AI Language service to extract linked entities.

Source: [Analyze text with Azure AI Language](https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/)

#### Chapter 2 - Create question answering solutions with Azure AI Language

Q:: =============================================

You want to create a knowledge base from an existing FAQ document. What should you do?
- Create an empty knowledge base and manually enter the FAQ questions and answers.
- Create a new knowledge base, importing the existing FAQ document.
- Create a new knowledge base, selecting only the Professional chit-chat source.

A:: =============================================

Create a new knowledge base, importing the existing FAQ document.

Source: [Create question answering solutions with Azure AI Language](https://learn.microsoft.com/en-us/training/modules/create-question-answer-solution-ai-language/)

Q:: =============================================

How can you add a multi-turn context for a question in an existing knowledge base?
- Add synonyms to the knowledge base.
- Add alternative phrasing to the question.
- Add a follow-up prompt to the question.

A:: =============================================

Add a follow-up prompt to the question.

Source: [Create question answering solutions with Azure AI Language](https://learn.microsoft.com/en-us/training/modules/create-question-answer-solution-ai-language/)

Q:: =============================================

How can you enable users to use your knowledge base through email?
- Add Friendly Chit-chat to the knowledge base.
- Enable Active Learning for the knowledge base and include the user's email address as the user
parameter in responses.
- Create a bot based on your knowledge base and configure an email channel.

A:: =============================================

Create a bot based on your knowledge base and configure an email channel.

Source: [Create question answering solutions with Azure AI Language](https://learn.microsoft.com/en-us/training/modules/create-question-answer-solution-ai-language/)

#### Chapter 3 - Build a conversational language understanding model

Q:: =============================================

Your app must interpret a command such as "turn on the light" or "switch the light on". What do these phrases represent in a language model?
- Intents.
- Utterances.
- Entities.

A:: =============================================

Utterances.

Source: [Build a conversational language understanding model](https://learn.microsoft.com/en-us/training/modules/build-language-understanding-model/)

Q:: =============================================

Your app must interpret a command to book a flight to a specified city, such as "Book a flight to Paris." How should you model the city element of the command?
- As an intent.
- As an utterance.
- As an entity.

A:: =============================================

As an entity.

Source: [Build a conversational language understanding model](https://learn.microsoft.com/en-us/training/modules/build-language-understanding-model/)

Q:: =============================================

Your language model needs to detect an email when present in an utterance. What is the simplest way to extract that email?
- Use Regular Expression entities.
- Use prebuilt entity components.
- Use Learned entity components.

A:: =============================================

Use prebuilt entity components.

Source: [Build a conversational language understanding model](https://learn.microsoft.com/en-us/training/modules/build-language-understanding-model/)

#### Chapter 4 - Create custom text classification solutions

Q:: =============================================

You want to train a model to classify book summaries by their genre, and some of your favorite books are both mystery and thriller. Which type of project should you build?
- A single label classification project
- A multiple label classification project
- A varied label classification project

A:: =============================================



Source: [Create custom text classification solutions](https://learn.microsoft.com/en-us/training/modules/custom-text-classification/)

Q:: =============================================

You just got notification your training job is complete. What is your next step?
- Label more data
- Deploy your model
- View your model details

A:: =============================================



Source: [Create custom text classification solutions](https://learn.microsoft.com/en-us/training/modules/custom-text-classification/)

Q:: =============================================

You want to submit a classification task via the API. How do you get the results of the classification?
- The result is in the response of the classification request.
- Call an endpoint with your deployment name to get the most recent classification.
- Call the URL prov
ed in the header of the request response.

A:: =============================================



Source: [Create custom text classification solutions](https://learn.microsoft.com/en-us/training/modules/custom-text-classification/)

#### Chapter 5 - Custom named entity recognition

Q:: =============================================

You've trained your model and you're seeing that it doesn't recognize your entities. What metric score is likely low to indicate that issue?
- Recall
- Precision
- F1 score

A:: =============================================

Recall

Source: [Custom named entity recognition](https://learn.microsoft.com/en-us/training/modules/custom-name-entity-recognition/)

Q:: =============================================

You just finished labeling your data. How and where is that file stored to train your model?
- JSON file, in my storage account container for the project
- XML file, in my local project folder
- YAML file, anywhere in my Azure account

A:: =============================================

JSON file, in my storage account container for the project

Source: [Custom named entity recognition](https://learn.microsoft.com/en-us/training/modules/custom-name-entity-recognition/)

Q:: =============================================

You train your model with only one source of documents, even though real extraction tasks will come from several sources. What data quality metric do you need to increase?
- Distribution
- Accuracy
- Diversity

A:: =============================================

Diversity

Source: [Custom named entity recognition](https://learn.microsoft.com/en-us/training/modules/custom-name-entity-recognition/)

#### Chapter 6 - Translate text with Azure AI Translator service

Q:: =============================================

What function of Azure AI Translator should you use to convert the Chinese word "你好" to the English word "Hello"?
- Detect
- Translate
- Transliterate

A:: =============================================



Source: [Translate text with Azure AI Translator service](https://learn.microsoft.com/en-us/training/modules/translate-text-with-translator-service/)

Q:: =============================================

What function of Azure AI Translator should you use to convert the Russian word "спасибо" in Cyrillic characters to "spasibo" in Latin characters?
- Detect
- Translate
- Transliterate

A:: =============================================



Source: [Translate text with Azure AI Translator service](https://learn.microsoft.com/en-us/training/modules/translate-text-with-translator-service/)

#### Chapter 7 - Create speech-enabled apps with Azure AI services

Q:: =============================================

What information do you need from your Azure AI Speech service resource to consume it using the Azure AI Speech SDK?
- The location and one of the keys
- The primary and secondary keys
- The endpoint and one of the keys

A:: =============================================

The location and one of the keys

Source: [Create speech-enabled apps with Azure AI services](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/)

Q:: =============================================

Which object should you use to specify that the speech input to be transcribed to text is in an audio file?
- SpeechConfig
- AudioConfig
- SpeechRecognizer

A:: =============================================

AudioConfig

Source: [Create speech-enabled apps with Azure AI services](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/)

Q:: =============================================

How can you change the voice used in speech synthesis?
- Specify a SpeechSynthesisOutputFormat enumeration in the SpeechConfig object.
- Set the SpeechSynthesisVoiceName property of the SpeechConfig object to the desired voice name.
- Specify a filename in the AudioConfig object.

A:: =============================================

Set the SpeechSynthesisVoiceName property of the SpeechConfig object to the desired voice name.

Source: [Create speech-enabled apps with Azure AI services](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/)

#### Chapter 8 - Translate speech with the Azure AI Speech service

Q:: =============================================

Which SDK object should you use to specify the language(s) into which you want speech translated?
- SpeechConfig
- SpeechTranslationConfig
- AudioConfig

A:: =============================================

SpeechTranslationConfig

Source: [Translate speech with the Azure AI Speech service](https://learn.microsoft.com/en-us/training/modules/translate-speech-speech-service/)

Q:: =============================================

Which SDK object should you use as a proxy for the Translation API of Azure AI Speech service?
- TranslationRecognizer
- SpeechRecognizer
- SpeechSynthesizer

A:: =============================================

TranslationRecognizer

Source: [Translate speech with the Azure AI Speech service](https://learn.microsoft.com/en-us/training/modules/translate-speech-speech-service/)

Q:: =============================================

When translating speech, in which cases can you use the Synthesizing event to synthesize the translations and speech?
- Only when translating to a single target language.
- Only when translating to multiple target languages.
- When translating to one or more target languages.

A:: =============================================

Only when translating to a single target language.

Source: [Translate speech with the Azure AI Speech service](https://learn.microsoft.com/en-us/training/modules/translate-speech-speech-service/)

#### Chapter 9 - Develop an audio-enabled generative AI application

Q:: =============================================

Which kind of model can you use to respond to audio input?
- Only OpenAI GPT models
- Embedding models
- Multimodal models

A:: =============================================

Multimodal models

Source: [Develop an audio-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-audio-apps/)

Q:: =============================================

How can you submit a prompt that asks a model to analyze an audio file?
- Submit one prompt with an audio-based message followed by another prompt with a text-based message.
- Submit a prompt that contains a multi-part user message, containing both text content and audio content.
- Submit the audio file as the system message and the instruction or question as the user message.

A:: =============================================

Submit a prompt that contains a multi-part user message, containing both text content and audio content.

Source: [Develop an audio-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-audio-apps/)

Q:: =============================================

How can you include an audio in a message?
- As a URL or as binary data
- Only as a URL
- Only as binary data

A:: =============================================

As a URL or as binary data

Source: [Develop an audio-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-audio-apps/)

#### Chapter 10 - Develop an Azure AI Voice Live agent

Q:: =============================================

What are the two authentication methods supported by the Voice Live API?
- OAuth 2.0 and JWT (JSON Web Tokens)
- Basic authentication and API keys
- Microsoft Entra (keyless) and API key

A:: =============================================

Microsoft Entra (keyless) and API key

Source: [Develop an Azure AI Voice Live agent](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

Q:: =============================================

Which scope is required when generating a token for Microsoft Entra authentication?
- https://cognitiveservices.azure.com/.default
- https://management.azure.com/.default
- https://graph.microsoft.com/.default

A:: =============================================

https://cognitiveservices.azure.com/.default

Source: [Develop an Azure AI Voice Live agent](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

Q:: =============================================

Which protocol is used for avatar streaming integration in Voice Live API?
- HTTP/2
- WebRTC
- gRPC

A:: =============================================

WebRTC

Source: [Develop an Azure AI Voice Live agent](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

Q:: =============================================

Which event should be handled to stop audio playback when a user interrupts the voice agent?
- ServerEventType.RESPONSE_AUDIO_DELTA
- ServerEventType.INPUT_AUDIO_BUFFER_SPEECH_STARTED
- ServerEventType.SESSION_UPDATED

A:: =============================================

ServerEventType.INPUT_AUDIO_BUFFER_SPEECH_STARTED

Source: [Develop an Azure AI Voice Live agent](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

Q:: =============================================

What is the recommended authentication method for production applications using the SDK?
- API key authentication
- Microsoft Entra authentication with DefaultAzureCredential
- Basic username/password authentication

A:: =============================================

Microsoft Entra authentication with DefaultAzureCredential

Source: [Develop an Azure AI Voice Live agent](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

### Part IV - Develop computer vision solutions in Azure

#### Chapter 1 - Analyze images

Q:: =============================================

What is the purpose of Azure AI Vision Image Analysis?
- To prov
e reporting and auditing of virtual machine templates in your Azure subscriptions
- To extract information about visual features in images
- To support v
eo conferencing and web-cam communication

A:: =============================================

To extract information about visual features in images

Source: [Analyze images](https://learn.microsoft.com/en-us/training/modules/analyze-images/)

Q:: =============================================

You want to use Azure AI Vision Image Analysis to generate suggested text descriptions for an image. Which visual feature should you specify?
- Tags
- DenseCaptions
- Read

A:: =============================================

DenseCaptions

Source: [Analyze images](https://learn.microsoft.com/en-us/training/modules/analyze-images/)

#### Chapter 2 - Read text in images

Q:: =============================================

Which service should you use to locate and read text in signs within a photograph of a street?
- Azure AI Language Named Entity Recognition
- Azure AI Document Intelligence
- Azure AI Vision Image Analysis

A:: =============================================

Azure AI Vision Image Analysis

Source: [Read text in images](https://learn.microsoft.com/en-us/training/modules/read-text-images-documents-with-computer-vision-service/)

Q:: =============================================

Which visual feature enumeration should you use to return OCR results from an image analysis call?
- VisualFeatures.Caption
- VisualFeatures.Read
- VisualFeatures.Tags

A:: =============================================

VisualFeatures.Read

Source: [Read text in images](https://learn.microsoft.com/en-us/training/modules/read-text-images-documents-with-computer-vision-service/)

Q:: =============================================

Text location information in an image is returned at which levels by Azure AI Vision Image Analysis?
- The location of indiv
ual words only.
- A single block containing all of the text in the image.
- A block containing the location of lines of text as well as indiv
ual words.

A:: =============================================

A block containing the location of lines of text as well as indiv
ual words.

Source: [Read text in images](https://learn.microsoft.com/en-us/training/modules/read-text-images-documents-with-computer-vision-service/)

#### Chapter 3 - Detect, analyze, and recognize faces

Q:: =============================================

You need to create a facial recognition solution to 
entify named employees. Which service should you use?
- Azure AI Vision Image Analysis.
- Azure AI Vision Custom Vision.
- Azure AI Vision Face.

A:: =============================================

Azure AI Vision Face.

Source: [Detect, analyze, and recognize faces](https://learn.microsoft.com/en-us/training/modules/detect-analyze-recognize-faces/)

Q:: =============================================

What should you return when analyzing an image to see the spatial points related to facial features?
- Accessories
- Landmarks
- HeadPose

A:: =============================================

Landmarks

Source: [Detect, analyze, and recognize faces](https://learn.microsoft.com/en-us/training/modules/detect-analyze-recognize-faces/)

#### Chapter 4 - Classify images

Q:: =============================================

What Azure AI Custom Vision resources should you create in Azure to create a custom vision solution?
- A single Computer Vision resource
- A Custom Vision resource for image classification, and another for object detection
- A Custom Vision resource for training, and another for prediction

A:: =============================================

A Custom Vision resource for training, and another for prediction

Source: [Classify images](https://learn.microsoft.com/en-us/training/modules/classify-images/)

Q:: =============================================

You want to train a model that can categorize an image as "cat" or "dog" based on its subject. What kind of Azure AI Custom Vision project should you create?
- Image classification (multiclass)
- Image classification (multilabel)
- Object detection

A:: =============================================

Image classification (multiclass)

Source: [Classify images](https://learn.microsoft.com/en-us/training/modules/classify-images/)

Q:: =============================================

What information does a client application need to connect to Azure AI Custom Vision and classify an image?
- The endpoint and key for the Custom Vision training resource
- The endpoint and key for the Custom Vision prediction resource
- The endpoint and key for the Custom Vision prediction resource, the project 
for your image classification project, and the name of your deployed model

A:: =============================================

The endpoint and key for the Custom Vision prediction resource, the project 
for your image classification project, and the name of your deployed model

Source: [Classify images](https://learn.microsoft.com/en-us/training/modules/classify-images/)

#### Chapter 5 - Detect objects in images

Q:: =============================================

What does an object detection model predict?
- The location and class of specific classes of object in an image.
- The class of the main subject of an image.
- The file type of an image.

A:: =============================================

The location and class of specific classes of object in an image.

Source: [Detect objects in images](https://learn.microsoft.com/en-us/training/modules/detect-objects-images/)

Q:: =============================================

What must you do before taking advantage of the smart labeler tool when creating an object detection model?
- Create a JSON file containing bounding box coordinates.
- Tag some images with objects of each class and train an initial object detection model.
- Train an image classification (multilabel) model.

A:: =============================================

Tag some images with objects of each class and train an initial object detection model.

Source: [Detect objects in images](https://learn.microsoft.com/en-us/training/modules/detect-objects-images/)

#### Chapter 6 - Analyze v
eo

Q:: =============================================

You want Azure V
eo Indexer to analyze a v
eo. What must you do first?
- Use the Azure AI Vision service to extract key frames from the v
eo.
- Upload the v
eo to Azure V
eo Indexer and index it.
- Store the v
eo file in an Azure blob store container.

A:: =============================================

Upload the v
eo to Azure V
eo Indexer and index it.

Source: [Analyze v
eo](https://learn.microsoft.com/en-us/training/modules/analyze-v
eo/)

Q:: =============================================

You want Azure V
eo Indexer to recognize brands in v
eos recorded from conference calls. What should you do?
- Edit the Brands model to show brands suggested by Bing, and add any new brands you want to detect.
- Edit all recorded conference call v
eos to include a caption of each brand seen on their first appearance.
- Embed the Azure V
eo Indexer w
gets in a custom web site.

A:: =============================================

Edit the Brands model to show brands suggested by Bing, and add any new brands you want to detect.

Source: [Analyze v
eo](https://learn.microsoft.com/en-us/training/modules/analyze-v
eo/)

#### Chapter 7 - Develop a vision-enabled generative AI application

Q:: =============================================

Which kind of model can you use to respond to visual input?
- Only OpenAI GPT models
- Embedding models
- Multimodal models

A:: =============================================

Multimodal models

Source: [Develop a vision-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/)

Q:: =============================================

How can you submit a prompt that asks a model to analyze an image?
- Submit one prompt with an image-based message followed by another prompt with a text-based message.
- Submit a prompt that contains a multi-part user message, containing both text content and image content.
- Submit the image as the system message and the instruction or question as the user message.

A:: =============================================

Submit a prompt that contains a multi-part user message, containing both text content and image content.

Source: [Develop a vision-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/)

Q:: =============================================

How can you include an image in a message?
- As a URL or as binary data
- Only as a URL
- Only as binary data

A:: =============================================

As a URL or as binary data

Source: [Develop a vision-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/)

#### Chapter 8 - Generate images with AI

Q:: =============================================

You want to use a model in Azure AI Foundry to generate images. Which model should you use?
- DALL-E
- GPT-4o
- text-embedding-ada-002

A:: =============================================

DALL-E

Source: [Generate images with AI](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/)

Q:: =============================================

Which playground in Azure AI Foundry portal should you use to test an image-generation model?
- Agents
- Chat
- Images

A:: =============================================

Images

Source: [Generate images with AI](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/)

Q:: =============================================

In a REST request to generate images, what does the n parameter indicate?
- The description of the desired image.
- The number of images to be generated
- The size of the image to be generated

A:: =============================================

The number of images to be generated

Source: [Generate images with AI](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/)

### Part V - Develop AI information extraction solutions in Azure

#### Chapter 1 - Create a multimodal analysis solution with Azure AI Content Understanding

Q:: =============================================

What kinds of AI solution is Azure AI Content Understanding designed to help you build?
- Chatbots that automatically translate between multiple spoken and written languages.
- Analyzers that extract information from documents, images, v
eos, and audio files.
- Image generators that create visualizations based on descriptions.

A:: =============================================

Analyzers that extract information from documents, images, v
eos, and audio files.

Source: [Create a multimodal analysis solution with Azure AI Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/)

Q:: =============================================

Which graphical tool should you use to create an Azure AI Content Understanding project?
- Microsoft Visual Studio.
- Azure Machine Learning studio.
- Azure AI Foundry portal.

A:: =============================================

Azure AI Foundry portal.

Source: [Create a multimodal analysis solution with Azure AI Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/)

Q:: =============================================

What should you define for the information you want to extract from content?
- A schema.
- An index.
- A cluster.

A:: =============================================

A schema.

Source: [Create a multimodal analysis solution with Azure AI Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/)

#### Chapter 2 - Create an Azure AI Content Understanding client application

Q:: =============================================

What configuration values are needed to use the Azure AI Content Understanding REST API?
- The name of the resource group where the Azure AI service is deployed.
- The Azure subscription 
and tenant 
.
- The endpoint and key for the Azure AI service.

A:: =============================================

The endpoint and key for the Azure AI service.

Source: [Create an Azure AI Content Understanding client application](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/)

Q:: =============================================

What must be specified when calling the analyze method to extract fields from content?
- The name of the Azure AI services resource.
- The name of the analyzer.
- The Operation-Location returned when the analyzer was created.

A:: =============================================

The name of the analyzer.

Source: [Create an Azure AI Content Understanding client application](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/)

Q:: =============================================

How are the extracted fields returned?
- As type-specific values.
- As a list of strings.
- As a single blob.

A:: =============================================

As type-specific values.

Source: [Create an Azure AI Content Understanding client application](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/)

#### Chapter 3 - Use prebuilt Document intelligence models

Q:: =============================================

You have a large set of documents with varying structures that contain customer name and address information. You want to extract entities for each customer. Which prebuilt model should you use?
- Read model.
- General document model.
- 
document model.

A:: =============================================

General document model.

Source: [Use prebuilt Document intelligence models](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/)

Q:: =============================================

You are using the prebuilt layout model to analyze a document with many checkboxes. You want to find out whether each box is checked or empty. What object should you use in the returned JSON code?
- Selection marks.
- Bounding boxes.
- Conf
ence indicators.

A:: =============================================

Selection marks.

Source: [Use prebuilt Document intelligence models](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/)

Q:: =============================================

You submit a Word document to the Azure AI Document Intelligence general document model for analysis but you receive an error. The file is A4 size, contains 1 MB of data, and is not password-protected. How should you resolve the error?
- Change from the free tier to the standard tier.
- Submit the document one page at a time.
- Convert the document to PDF format.

A:: =============================================

Convert the document to PDF format.

Source: [Use prebuilt Document intelligence models](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/)

#### Chapter 4 - Extract data from forms with Azure Document intelligence

Q:: =============================================

A person plans to use an Azure Document Intelligence prebuilt invoice model. To extract document data using the model and REST API language, what are two calls they need to make to the API?
- Train Model and Get Model Labels
- Analyze Invoice and Get Analyze Invoice Result
- Create Azure Document Intelligence and Get Analyze Invoice Result

A:: =============================================

Analyze Invoice and Get Analyze Invoice Result

Source: [Extract data from forms with Azure Document intelligence](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/)

Q:: =============================================

A person needs to build an application that submits expense claims and extracts the merchant, date, and total from scanned receipts. What's the best way to build the application?
- Use the Read API of the Computer Vision service.
- Use Azure Document Intelligence's prebuilt receipts model
- Use Azure Document Intelligence's Layout service

A:: =============================================

Use Azure Document Intelligence's prebuilt receipts model

Source: [Extract data from forms with Azure Document intelligence](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/)

Q:: =============================================

A person is building a custom model with Azure Document Intelligence services. What is required to train a model?
- Along with the form to analyze, JSON files need to be prov
ed.
- Training must be done through language-specific SDKs.
- Nothing else is required.

A:: =============================================

Along with the form to analyze, JSON files need to be prov
ed.

Source: [Extract data from forms with Azure Document intelligence](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/)

#### Chapter 5 - Create a knowledge mining solution with Azure AI Search

Q:: =============================================

Which component of an Azure AI Search solution is scheduled to extract and enrich data to populate an index?
- Indexer
- Projection
- Query

A:: =============================================

Indexer

Source: [Create a knowledge mining solution with Azure AI Search](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/)

Q:: =============================================

Which service supports built-in AI skills in Azure AI Search?
- Azure Functions
- Azure AI services
- Azure Cosmos DB

A:: =============================================

Azure AI services

Source: [Create a knowledge mining solution with Azure AI Search](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/)

Q:: =============================================

Which kind of projection results in a relational data schema for extracted fields?
- File
- Object
- Table

A:: =============================================

Table

Source: [Create a knowledge mining solution with Azure AI Search](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/)

### Part VI - Microsoft test-like questions

#### Chapter 1 - Questions

Q:: =============================================

You are building an app named App1 that uses the Image Analysis API.
You are evaluating analyzing images by using the following request.
https://*.cognitiveservices.azure.com/computervision/imageanalysis:analyze? features=read,description
Which results will the request return?

Select only one answer.

- a description of the image content only
- the visible text in the image and a description of the image content
- which objects there are in the image and their approximate location

A:: =============================================

1. the visible text in the image and a description of the image content

The features used in the call are `read` and `description`, which will return the visible text in the image, as well as a description of the image content.
To return the objects that are in the image and their approximate location, the feature used in the call should be `objects`. To return a description of the image content only, the feature `description` should be used alone.

[Call the Image Analysis API - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/how-to/call-analyze-image?tabs=rest)

[Read Text in Images and Documents with the Computer Vision Service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-images-documents-with-computer-vision-service/)

Q:: =============================================

You are building an app that will detect the color scheme of uploaded images.
You are evaluating using the Image Analysis API to detect the dominant background color of an image.
Which color can the API return as a dominant background color?

Select only one answer.

- azure
- maroon
- silver
- teal

A:: =============================================

1. teal

Only a certain set of colors can be returned by the API. The set of possible returned colors is black, blue, brown, gray, green, orange, pink, purple, red, teal, white, and yellow.

[Color scheme detection - Computer Vision - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/concept-detecting-color-schemes)

[Analyze images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images/)

Q:: =============================================

You are building an app that will use Azure AI Vision to extract text from scanned images of handwritten text.
Which Azure AI Vision feature should you use?

Select only one answer.

- Azure AI Custom Vision
- handwriting analysis
- Image Analysis
- optical character recognition (OCR)
- Spatial Analysis

A:: =============================================

1. optical character recognition (OCR)

OCR is the only visual feature that can extract text from images.

[What is Computer Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview)

[Read Text in Images and Documents with the Computer Vision Service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-images-documents-with-computer-vision-service/)

Q:: =============================================

You are creating a model to detect animals in wildlife images.
You need to train a model that entifies and locates animals efficiently.
What should you use?

Select only one answer.

- Build a CNN model by using Azure Machine Learning.
- Train a classification model by using Azure Custom Vision.
- Use Azure Custom Vision to train an object detection model.
- Use the prebuilt image tagging model in Azure AI Vision.

A:: =============================================

1. Use Azure Custom Vision to train an object detection model.

Using Azure Custom Vision to train an object detection model is the optimal choice because it meets the requirements for entifying and locating animals in wildlife images. Building a CNN model by using Azure Machine Learning is resource-intensive and unnecessary given the availability of Azure Custom Vision. Training a classification model by using Azure Custom Vision does not prove localization information, which is essential for this task. Using the prebuilt image tagging model in Azure AI Vision lacks customization and localization capabilities, making it unsuitable for this scenario.\

[Enrich a search index in Azure AI Search with custom classes and Azure AI Language - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/enrich-search-index-using-language-studio/03-enrich-cognitive-search-index-custom-classes)


[Get started with Azure Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)

Q:: =============================================

You are developing a custom vision model using Microsoft Azure Custom Vision to classify images of various food items. The dataset includes images labeled as 'vegetable-fruit', 'dessert', and 'soup'.
You need to optimize the training process to improve the model's performance metrics.
Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

- Select the 'Food' domain.
- Select the 'General' domain.
- Set a high probability threshold during training.
- Use consistent tags to label images.

A:: =============================================

1. Select the 'Food' domain.
2. Use consistent tags to label images.

Using consistent tags to label images ensures that the model can accurately associate visual features with their respective categories, which is essential for effective training. Selecting the 'Food' domain optimizes the model for food-related image classification tasks, leveraging domain-specific features to enhance performance. Setting a high probability threshold during training is not suitable because it could reduce recall by limiting the number of classifications detected. Similarly, selecting the 'General' domain is not eal as it lacks the specialization required for food-related tasks, potentially leading to suboptimal results.

[Understand types of classification projects - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/custom-text-classification/2-understand-types-of-classification-projects)


[Select a domain for a Custom Vision project - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/select-domain)

Q:: =============================================

You are building an app that uses the Azure AI Veo indexer API to analyze Microsoft Teams meeting recordings. The app will search for images and mentions of competing companies.
Which content model should you use?

Select only one answer.

- custom brands
- custom Language
- custom slate

A:: =============================================

1. custom brands

The Custom Brands model supports brand detection from speech and visuals.
Slate detection is used for clapper boards and digital patterns with color bars, and the custom Language model is used to add words that are not in the model.

[Customize a Brands model in Azure Veo Indexer - Azure - Azure Veo Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-veo-indexer/customize-brands-model-overview)

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-veo/)

Q:: =============================================

You are building a veo processing app that will use Azure AI Veo Indexer.
You need to configure the training and learning phases for the app. The solution must train the model based on the probability of specific word combinations by using a custom Language model.
Which three practices should be followed for the training data? Each correct answer presents a complete solution.

Select all answers that apply.

- Include at least 500,000 sentences.
- Include multiple examples of spoken sentences.
- Include special characters such as ~, #, @, %, and &.
- Prove multiple adaptation options.
- Put only one sentence per line.
- Repeat the entical sentence multiple times.

A:: =============================================

1. Include multiple examples of spoken sentences.
2. Prove multiple adaptation options.
3. Put only one sentence per line.

When training the model, you should avorepeating an entical sentence multiple times, as it may create bias against the rest of the input.
You should avoincluding uncommon symbols (~, # @ % &), as they will be discarded. The sentences in which they appear will also be discarded.
You should also avoputting inputs that are too large, such as hundreds of thousands of sentences, because doing so will dilute the effect of boosting.

[Customize a Language model in Azure Veo Indexer - Azure - Azure Veo Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-veo-indexer/customize-language-model-overview)

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-veo/)

Q:: =============================================

You are building a veo processing app that will use Azure AI Veo Indexer to extract insights from veos that contain multi-language content.
You need to configure the API calls to enable multilingual entification.
Which value should you set for the `sourceLanguage` parameter?

Select only one answer.

- `language detection`
- `multi detection`
- `multi-language detection `
- `multi-lingual detection `

A:: =============================================

1. `multi-language detection `

When indexing or reindexing a veo by using the API, choose the multi-language detection option for the `sourceLanguage` parameter. The remaining options do not configure the API calls to enable multilingual entification.

[Automatically entify and transcribe multi-language content with Azure Veo Indexer - Azure Veo Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-veo-indexer/multi-language-entification-transcription)

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-veo/)

Q:: =============================================

You are building a solution that uses Azure AI Search.
You need to save normalized binary files as projections.
Which type of projection should you use?

Select only one answer.

- files
- objects
- tables

A:: =============================================

1. files

Tables are used for data that is best represented as rows and columns, or whenever you need granular representations of your data.
Files are used when you need to save normalized, binary image files. Objects are used when you need the full JSON representation of your data and enrichments in one JSON document.

[Projection concepts - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/knowledge-store-projection-overview#types-of-projections-and-usage)

[Create an Azure Cognitive Search solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are building an app will use Azure AI Search.
You need to index a collection of documents.
What is the first stage of the indexing process?

Select only one answer.

- document cracking
- field mapping
- output field mapping
- push into index
- skillset execution

A:: =============================================

1. document cracking

Document cracking is the process of opening files and extracting content. It is the first stage of the indexing process.
Text-based content can be extracted from files in a service, rows in a table, or items in a container or collection. If you add a skillset and image skills, document cracking can also extract images and queue them for image processing.

[Indexer overview - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/search-indexer-overview)

[Create an Azure Cognitive Search solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are building a knowledge mining solution that will use AI enrichment and Azure AI Search.
You need to create a data structure that will be used to store the enriched and indexed output for downstream apps.
What should you create?

Select only one answer.

- a knowledge store
- a searchable index
- a searchable store
- an enrichment cache

A:: =============================================

1. a knowledge store

A knowledge store is used for downstream apps, such as knowledge mining and data science. A knowledge store is defined within a skillset. Its definition determines whether your enriched documents are projected as tables or objects (files or blobs) in Azure Storage.

[AI enrichment concepts - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-concept-intro)

[Create a knowledge store with Azure Cognitive Search - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-knowledge-store-azure-cognitive-search/)

Q:: =============================================

Your company collects cards during networking events and needs to automate processing to store contact information in a database.
You need to extract contact details such as names, email addresses, and phone numbers from the business cards.
What should you use to achieve this goal?

Select only one answer.

- Train a custom model in Azure AI Document Intelligence Studio.
- Use Azure AI Vision OCR.
- Use the Business Card model in Azure AI Document Intelligence.
- Use the Document model in Azure AI Document Intelligence.

A:: =============================================

1. Use the Business Card model in Azure AI Document Intelligence.

The Business Card model in Azure AI Document Intelligence is the optimal choice for processing business cards due to its specialized capabilities for extracting structured data such as names, email addresses, and phone numbers. Training a custom model is unnecessary because the Business Card model already meets the requirements. Azure AI Vision OCR lacks the ability to extract structured data, making it unsuitable for this task. The Document model is designed for entity documents and does not prove the necessary functionality for processing business cards.

[Use the Azure Document Intelligence Studio - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/9-form-recognizer-studio)


[Use financial, , and tax models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/4-use-financial--tax-models)

Q:: =============================================

Your organization processes a large volume of scanned vendor documents, some of which are poorly scanned or contain creases.
You need to extract structured data such as vendor details, totals, and line items from these invoices.
What should you use to achieve this goal?

Select only one answer.

- Train a custom model in Azure AI Document Intelligence Studio.
- Use Azure AI Vision OCR.
- Use the Invoice model in Azure AI Document Intelligence.
- Use the Business Card model in Azure AI Document Intelligence.

A:: =============================================

1. Use the Invoice model in Azure AI Document Intelligence.

The Invoice model in Azure AI Document Intelligence is the optimal choice for processing invoices due to its specialized capabilities for extracting structured data, even from poorly scanned documents. Training a custom model is unnecessary because the Invoice model already meets the requirements. Azure AI Vision OCR lacks the ability to extract structured data, making it unsuitable for this task. The Business Card model is designed for business cards and does not prove the necessary functionality for processing invoices.

[Use financial, , and tax models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/4-use-financial--tax-models)

Q:: =============================================

Your company receives incoming documents that need to be classified into predefined categories before extracting specific data fields.
You need to implement a solution that accurately classifies documents and supports subsequent data extraction.
Which solution should you recommend?

Select only one answer.

- Azure AI Vision OCR (Optical Character Recognition)
- Custom classification model in Azure AI Document Intelligence
- Custom template model in Azure AI Document Intelligence
- Invoice model in Azure AI Document Intelligence

A:: =============================================

1. Custom classification model in Azure AI Document Intelligence

The custom classification model in Azure AI Document Intelligence is the most suitable solution because it is specifically designed to categorize documents into predefined categories, enabling accurate classification and supporting subsequent data extraction. Custom template models are limited to data extraction from structured documents and do not address classification needs. Azure AI Vision OCR focuses solely on text recognition and lacks the functionality required for document categorization. The Invoice model is tailored for invoice processing and does not meet the broader requirements for document classification described in the scenario.

[What is Azure Document Intelligence? - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/2-what-form-recognizer)


[Use financial, , and tax models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/4-use-financial--tax-models)

Q:: =============================================

Your organization processes invoices from vendors in various formats, including scanned PDFs and digital images.
You need to implement Azure AI Document Intelligence to extract key fields such as invoice number, due date, and total amount.
Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

- Create a custom model for invoice processing.
- Install the solution on a local server.
- Label all invoice documents manually.
- Provision an Azure AI Document Intelligence resource.
- Edit the invoices to ensure consistency.
- Use the prebuilt invoice model to extract key fields.

A:: =============================================

1. Provision an Azure AI Document Intelligence resource.
2. Use the prebuilt invoice model to extract key fields.

To implement the solution, provisioning the Azure AI Document Intelligence resource is a necessary first step to enable its capabilities. Using the prebuilt invoice model is the most efficient approach for extracting key fields such as invoice number, due date, and total amount, as it is specifically designed for this purpose. Installing the solution on a local server is irrelevant because the service is cloud-based and does not require local installation. Creating a custom model is unnecessary because the prebuilt invoice model already meets the requirements, saving time and effort. Manually labeling invoice documents is also not needed, as the prebuilt model leverages pre-trained capabilities to eliminate this step. Editing the invoices to ensure consistency won't help when processing incoming invoices and doesn't prove the model with varied training data

[Document Intelligence invoice model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/invoice)

Q:: =============================================

An organization manually processes a high volume of invoices daily, leading to errors in data extraction.
You need to use Microsoft Azure AI Document Intelligence to automate invoice data extraction and integration.
Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

- Integrate the extracted data with an organization's database.
- Train a custom model for document processing.
- Use a general-purpose model for text extraction.
- Use the prebuilt Invoice model for data extraction.

A:: =============================================

1. Integrate the extracted data with an organization's database.
2. Use the prebuilt Invoice model for data extraction.

Integrating the extracted data with an organization's database ensures the information is stored and used effectively within existing systems, supporting downstream processes and workflows. Using the prebuilt Invoice model for data extraction is eal because it is specifically designed to handle invoice documents, extracting structured data such as key-value pairs and tables efficiently. Training a custom model for document processing is unnecessary in this scenario since the prebuilt Invoice model meets the requirements for standard invoices. Using a general-purpose model for text extraction does not align with the goal of extracting structured data from invoices, as it lacks the specificity required for this task.

[What is Azure Document Intelligence? - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/2-what-form-recognizer)


[Understand AI Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/2-understand)

Q:: =============================================

Your organization processes sensitive documents, such as contracts and invoices, and must comply with data privacy regulations.
You need to use Microsoft Azure AI Document Intelligence to automate structured data extraction from these documents.
Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

- Configure an Azure AI Search resource.
- Manually preprocess documents to remove sensitive information.
- Upload documents to Azure Blob Storage.
- Use the General Document model.
- Use the Layout model.

A:: =============================================

1. Upload documents to Azure Blob Storage.
2. Use the Layout model.

Uploading documents to Azure Blob Storage ensures that the documents are secure and accessible for processing and analysis. Using the Layout model is critical for extracting key-value pairs and entities from structured and semi-structured documents, directly addressing the requirements of the task. Manually preprocessing documents to remove sensitive information is unnecessary because Azure AI Document Intelligence can handle sensitive data without manual intervention. The General Document model is deprecated and no longer used. Configuring an Azure AI Search resource is not necessary for this task.

[Use the General Document, Read, and Layout models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/3-use-general-document-read-layout-models)

Q:: =============================================

Your company plans to deploy an AI agent to analyze customer feedback and generate insights from text.
You need to select the most suitable Azure AI Foundry Service for text analysis.
What should you recommend?

Select only one answer.

- Azure AI Language.
- Azure AI Speech.
- Azure AI Translator.
- Azure AI Vision.

A:: =============================================

1. Azure AI Language.

Azure AI Language is the most appropriate service for this scenario as it specializes in analyzing and deriving insights from natural language text, directly addressing the requirements for text analysis. Azure AI Speech is not suitable because it focuses on audio transformations such as speech-to-text and text-to-speech, which are unrelated to the task. Azure AI Translator is designed for translating text between languages and does not prove the necessary capabilities for analyzing and generating insights from text. Azure AI Vision is focused on image-related tasks and lacks the functionality required for processing natural language text.

[Plan and prepare to develop AI solutions on Azure - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-openai/5-deploy-models)


[Azure AI services - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: =============================================

Your organization is developing an AI agent for customer support inquiries that must integrate with Azure resources.
You need to select a framework that supports AI orchestration and multi-agent workflows.
What should you recommend?

Select only one answer.

- Azure Bot Framework
- Azure Machine Learning Studio
- Cognitive Services API
- Semantic Kernel framework

A:: =============================================

1. Semantic Kernel framework

Azure Bot Framework is commonly used for building conversational bots but does not prove the orchestration features required for multi-agent workflows. Azure Machine Learning Studio is focused on developing machine learning models and does not address the need for orchestration in this scenario. Cognitive Services API offers pre-built AI functionalities but lacks the ability to orchestrate multi-agent workflows. Semantic Kernel framework is the most suitable choice as it supports generative AI orchestration and multi-agent workflows, aligning perfectly with the requirements of the scenario.

[Provision an Azure AI Vision resource - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/analyze-images/2-provision-computer-vision-resource)


[Developer tools and SDKs - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: =============================================

Your organization is developing an AI agent to assist with document retrieval and analysis using Microsoft Azure services.
You need to enable the AI agent to access external data sources for processing documents.
What should you use?

Select only one answer.

- Configure a custom model in Azure Machine Learning.
- Enable default capabilities in Azure Document Intelligence.
- Use Azure AI Vision Service.
- Use Azure AI Search with built-in skills.

A:: =============================================

1. Use Azure AI Search with built-in skills.

Azure AI Search is the most suitable solution because it proves the required functionality for accessing and analyzing external documents with built-in skills, which aligns with the scenario's needs. Configuring a custom model in Azure Machine Learning focuses on document analysis but does not address the retrieval aspect, making it unsuitable. Enabling default capabilities in Azure Document Intelligence lacks the specific retrieval functionality needed for the task. Azure AI Vision Service can perform OCR but is not well suited for document processing and lacks the retrieval aspect.

[Developer tools and SDKs - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: =============================================

You are developing a custom AI agent using Azure AI Foundry Agent Service. The agent needs to interact with an Azure AI Foundry resource that has the GPT-35-Turbo model deployed.
You need to configure the agent to effectively use the GPT-35-Turbo model for generating responses.
What should you do?

Select only one answer.

- Deploy a GPT-4 model.
- Specify the GPT-35-Turbo deployment name.
- Use the Completion endpoint.
- Use the Embeddings endpoint.

A:: =============================================

1. Specify the GPT-35-Turbo deployment name.

To configure the agent to effectively use the GPT-35-Turbo model, specifying the deployment name ensures the agent interacts with the correct model deployed in a Microsoft Azure OpenAI resource. Using the Completion endpoint is not suitable for this model, as the ChatCompletion endpoint is preferred, and these endpoints aren't applicable to agents. Deploying a GPT-4 model does not meet the requirement to use the GPT-35-Turbo model specified in the scenario. The Embeddings endpoint is not appropriate for generating responses, as it serves a different purpose, such as creating vector representations of text.

[Get started with AI agent development on Azure - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

Q:: =============================================

You are developing an AI agent using Azure AI Foundry Agent Service to assist with data retrieval and analysis tasks.
You need to configure the AI agent to interact effectively with external data sources.
What should you use?

Select only one answer.

- Configure Azure AI Search.
- Deploy a custom model in Azure Machine Learning.
- Implement Azure Bot Framework.
- Use Azure AI Document Intelligence.

A:: =============================================

1. Configure Azure AI Search.

Configuring Azure AI Search is the most appropriate solution because it proves indexing and querying capabilities that enable effective interaction with external data sources. Deploying a custom model in Azure Machine Learning is not suitable as it focuses on model deployment rather than facilitating external data source interaction. Using Azure AI Document Intelligence is not appropriate because it is designed for extracting structured data from documents, which does not align with the broader goal of data retrieval and analysis. Implementing Azure Bot Framework is ineffective in this context as it is intended for building conversational interfaces and does not address the need for data retrieval and analysis.

[Developer tools and SDKs - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: =============================================

You are creating an assistant based on a generative Azure AI model.
You plan to use the system message component for prompts in the solution.
Which two capabilities does the system message offer for the model? Each correct answer presents part of the solution.

Select all answers that apply.

- defines the data sources that should not be included in the model
- defines what the model should and should not do
- detects which language is being used in a prompt
- helps define the assistant’s personality

A:: =============================================

1. defines what the model should and should not do
2. helps define the assistant’s personality

The system message is included at the beginning of the prompt and is used to prime the model with context, instructions, or other information relevant to the use case. You can use the system message to describe the assistant’s personality, define what the model should and should not answer, and define the format of model responses.

[Prompt engineering techniques with Azure OpenAI - Azure OpenAI Service | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/advanced-prompt-engineering?pivots=programming-language-chat-completions)

Q:: =============================================

You are provisioning an Azure OpenAI in Foundry Models service resource.
You need to ensure that the resource is only available to applications that are hosted in your Azure subscription.
Which network security setting should you configure?

Select only one answer.

- All networks
- All networks, and a network security group to control traffic
- Disabled, and allow a private endpoint connection to establish access
- Selected networks

A:: =============================================

1. Disabled, and allow a private endpoint connection to establish access

Because the requirements state that access to the resource should only be for applications hosted in the Azure subscription, setting the network option to Disabled and configuring a private endpoint meets this requirement.
All networks permit access to any network, including the internet. Selected networks access to networks outse of Azure, if configured that way.

[How-to: Create and deploy an Azure OpenAI Service resource - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/how-to/create-resource?pivots=web-portal)

Q:: =============================================

You are building a web app that will generate images based on user prompts. The app will use the DALL-E 3 Azure OpenAI model.
You need to ensure that HTTP requests against the Azure OpenAI API successfully generate images.
Which three HTTP header properties should you include? Each correct answer presents part of the solution.

Select all answers that apply.

- the API version used in this operation
- the name of the Azure OpenAI service resource
- the name of the DALL-E 3 model deployment
- the quality of the generated images
- the style of the generated images
- the user’s prompt

A:: =============================================

1. the API version used in this operation
2. the name of the Azure OpenAI service resource
3. the name of the DALL-E 3 model deployment

The name of the Azure OpenAI resource, the name of the DALL-E 3 model deployment, and the API version to be used are the three required header properties for HTTP requests. The other answers are valfor use in the HTTP body but not the header.

[Azure OpenAI Service REST API reference - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/reference)

Q:: =============================================

You are creating an application that will use Azure OpenAI REST API services. The application uses a REST call to a DALL-E model to generate images. The three parameters in the REST call are `prompt`, `n`, and `size`.
What does the `size` parameter indicate?

Select only one answer.

- the number of responses that you want returned
- the size of the images in bytes
- the size of the images in kilobytes
- the size of the images in pixel resolution

A:: =============================================

1. the size of the images in pixel resolution

To make a REST call to the services, you need the endpoint and authorization key for the Azure OpenAI service resource you provisioned in Azure. You initiate the image generation process by submitting a `POST` request to the service endpoint that has the authorization key in the header. The request must contain the following parameters in a JSON body:

- `prompt`: The description of the image to be generated

- `n`: The number of images to be generated

- `size`: The resolution of the image to be generated (*256x256*, *512x512*, or *1024x1024*)


[Use the Azure OpenAI REST API to consume DALL-E models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/generate-images-azure-openai/4-dall-e-rest-api)

Q:: =============================================

An organization plans to use Azure OpenAI in Foundry Models to process user input and generate content.
You need to create visual content from text descriptions.
What should you use?

Select only one answer.

- Azure AI Search
- DALL-E
- GPT-4
- Text Embedding Models

A:: =============================================

1. DALL-E

DALL-E is the appropriate choice for creating visual content from text descriptions, as it is specifically designed for this purpose. Azure Cognitive Search focuses on information retrieval and does not support visual content creation. GPT-4 is optimized for text-based tasks and lacks the capability to generate visual content. Text Embedding Models are intended for embedding tasks and are unrelated to the goal of creating visual content from text descriptions.

[Plan and prepare to develop AI solutions on Azure - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-openai/3-use-azure-openai-studio)


[Developer tools and SDKs - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/5-tools-and-sdks)

Q:: =============================================

Your organization plans to deploy a generative AI solution using Azure OpenAI in Foundry Models with GPT-4 for natural language responses.
You need to ensure GPT-4 is available for inferencing via an endpoint.
Which three actions should you perform to achieve this goal? Each correct answer presents part of the solution.

Select all answers that apply.

- Create a new Azure subscription.
- Deploy a GPT-4 model
- Provision a Azure AI Foundry resource.
- Select GPT-4 from the catalog.
- Set up a virtual machine.
- Use DALL-E.

A:: =============================================

1. Deploy a GPT-4 model
2. Provision a Azure AI Foundry resource.
3. Select GPT-4 from the catalog.

To deploy GPT-4 for inferencing, provisioning Azure AI Foundry resource is essential to establish the infrastructure. Selecting GPT-4 from the catalog ensures the correct model is chosen for the intended use case. Deploying GPT-4 to an endpoint makes it accessible for inferencing, completing the deployment process. Setting up a virtual machine is unnecessary because Azure AI Foundry uses managed endpoints. Creating a new Azure subscription is irrelevant if an existing subscription is available. Using DALL-E is incorrect because it is designed for image generation rather than natural language processing.

https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/3-deploy-model 

[Azure AI Foundry - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: =============================================

Your company uses an Azure OpenAI in Foundry Models service to generate images based on text prompts.
You need to configure the API request to ensure optimized image quality and resolution.
Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

- Set 'n' to 10.
- Set 'output_format' to JPEG.
- Set 'quality' to hd.
- Specify 'size' as 1024x1792.

A:: =============================================

1. Set 'quality' to hd.
2. Specify 'size' as 1024x1792.

To optimize image quality and resolution, 'quality' should be set to hd to ensure finer details and better consistency, and 'size' should be specified as 1024x1792 to meet the required resolution. Setting 'n' only determines the number of images generated and does not impact quality or resolution. Configuring 'output_format' affects the image format but does not influence image quality or resolution.

[How to use Azure OpenAI image generation models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dall-e?tabs=dalle-3)

Q:: =============================================

Your company uses an Azure OpenAI Foundry Models service to generate code snippets for software development.
You need to ensure the generated code adheres to your organization's coding standards.
What action should you take to achieve this?

Select only one answer.

- Enable multi-region deployment.
- Increase compute resources.
- Prove standard-compliant examples in prompts.
- Switch to a chat-optimized model.

A:: =============================================

1. Prove standard-compliant examples in prompts.

Proving examples of code adhering to standards in the input prompts ensures the AI model generates code that aligns with those standards, addressing the issue effectively. Enabling multi-region deployment enhances availability and resilience but does not impact code adherence to standards. Increasing compute resources may improve processing speed but does not affect code adherence to standards. Models optimized for chat-based interactions are not specifically designed to improve code adherence to standards.

[Prompt engineering techniques - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-engineering?tabs=chat)

Q:: =============================================

Your organization is using an Azure OpenAI in Foundry Models service for document summarization across various document types.
You need to ensure the AI generates summaries that meet organizational requirements.
What action should you take to achieve this?

Select only one answer.

- Enable diagnostic logging.
- Increase the token limit.
- Refine prompts to specify key details.
- Switch to a higher-cost model.

A:: =============================================

1. Refine prompts to specify key details.

Refining prompts to specify key details ensures the AI model generates concise and relevant summaries, directly addressing the optimization requirement. Enabling diagnostic logging proves insights into system performance but does not impact the quality of generated summaries. Increasing the token limit allows for longer responses but does not inherently improve quality. Switching to a higher-cost model may enhance performance but does not guarantee better summaries without prompt optimization.

[Prompt engineering techniques - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-engineering?tabs=chat)

Q:: =============================================

You have a website that allows users to upload images.
You need to ensure that the uploaded images do not contain adult content. The solution must minimize development effort.
Which service should you use?

Select only one answer.

- Azure AI Face Service
- Azure AI Custom Vision
- Azure AI Vision Image Analysis
- Azure AI Vision Spatial Analysis

A:: =============================================

1. Azure AI Vision Image Analysis

The Azure AI Vision Image Analysis service can extract a we variety of visual features from an image. One of them is to detect adult content.
The Azure AI Face service proves AI algorithms that detect, recognize, and analyze human faces in images. Azure AI Custom Vision is an image recognition service that lets you build, deploy, and improve own image entifier models. So, while it is possible, it is not the solution with the lowest development effort. Azure AI Vision Spatial Analysis is used to ingest streaming veo from cameras, extract insights, and generate events to be used by other systems.

[What are Azure Cognitive Services? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/what-are-cognitive-services)

[What is Computer Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview)

[What is Image Analysis? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview-image-analysis?tabs=3-2)

[Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

Q:: =============================================

You build an app that enables users to upload scans of invoices.
You need to extract text and key/value pairs from the scanned invoices.
Which service should you use?

Select only one answer.

- Azure AI Search
- Azure AI Document Intelligence
- Azure AI Immersive Reader
- Azure AI Metrics Advisor

A:: =============================================

1. Azure AI Document Intelligence

The Azure AI Document Intelligence is a service that lets you build automated data processing software by using machine learning technology. It allows you to entify and extract text and key/value pairs.
Azure AI Metrics Advisor uses AI to perform data monitoring and anomaly detection in time series data. Azure AI Immersive Reader is a tool that implements techniques to improve reading comprehension for new readers, language learners, and people with learning differences. Azure AI Search is a cloud search service to help you entify and explore relevant content at scale.

[What are Azure Applied AI Services? - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/what-are-applied-ai-services)

[Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

Q:: =============================================

You plan to implement a solution to extract information from documents by using Azure AI Document Intelligence and use prebuilt models where possible.
You need to entify the prebuilt models available in Azure AI Document Intelligence.
Which three models are available? Each correct answer presents a complete solution.

Select all answers that apply.

- invoice
- meeting minutes
- receipt
- time sheets
- W-2

A:: =============================================

1. invoice
2. receipt
3. W-2

Except for meeting minutes and time sheets, all the other models are prebuilt models in Azure AI Document Intelligence. Meeting minutes and time sheets must be added to Azure AI Document Intelligence. as custom models.

[Use financial, , and tax models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/use-prebuilt-form-recognizer-models/4-use-financial--tax-models)

Q:: =============================================

You are building a mobile app that will enable users to scan street signs and will read out the text on the sign.
You need to recommend a service to use. The solution must minimize development effort.
Which service should you recommend?

Select only one answer.

- Azure AI Vision
- Azure AI Custom Vision
- Azure AI Face Service
- Azure AI Document Intelligence

A:: =============================================

1. Azure AI Vision

Azure AI Vision is the only service which can achieve the desired result.
Azure AI Custom Vision and Azure AI Face do not offer OCR. Azure AI Document Intelligence is designed for documents, but not images.

[OCR - Optical Character Recognition - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview-ocr)

[Read Text in Images and Documents with the Computer Vision Service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-images-documents-with-computer-vision-service/)

Q:: =============================================

You are building an app that will extract text from scanned receipts.
You need to recommend which service to use. The solution must minimize development effort.
What should you recommend?

Select only one answer.

- Azure AI Vision
- Azure AI Custom Vision
- Azure AI Document Intelligence
- Azure Machine Learning

A:: =============================================

1. Azure AI Document Intelligence

Azure AI Document Intelligence is designed to work with documents such as receipts, as it offers prebuilt models for extracting information from these kinds of documents.

[OCR - Optical Character Recognition - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview-ocr)

[Extract data from forms with Form Recognizer - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/work-form-recognizer/)

Q:: =============================================

Your company plans to develop an app with an AI model using proprietary data.
You need to select an Azure platform to ensure the model is connected and operationalized effectively.
Which Azure platform should you recommend?

Select only one answer.

- Azure AI Content Understanding
- Azure AI Speech
- Azure AI Vision
- Azure AI Foundry

A:: =============================================

1. Azure AI Foundry

Azure AI Foundry is the most appropriate platform because it offers specialized tools for deploying models, connecting data, and managing AI resources. Azure AI Content Understanding focuses on multimodal content analysis and does not support custom model development. Azure AI Speech is designed for speech-related tasks and lacks the necessary features for connecting or operationalizing generative AI models. Azure AI Vision is tailored for prebuilt computer vision models and does not meet the requirements for AI model development.

[Azure AI services - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)

Q:: =============================================

Your company is deploying a generative AI model using Microsoft Azure AI Foundry Service to assist customer support agents by proving suggested responses to user queries.
You need to ensure the model generates outputs that are safe and free from harmful content.
Each correct answer presents part of the solution. Which three actions should you take?

Select all answers that apply.

- Conduct red team exercises to test vulnerabilities.
- Document the model's decision-making logic.
- Enable users to prove feedback on responses.
- Integrate Azure AI Foundry Content Safety APIs.
- Train the model exclusively on synthetic data.

A:: =============================================

1. Conduct red team exercises to test vulnerabilities.
2. Document the model's decision-making logic.
3. Integrate Azure AI Foundry Content Safety APIs.

Conducting red team exercises helps entify vulnerabilities and improve the model's robustness against manipulation. This enhances the security and reliability of the AI system. Documenting the model's decision-making logic proves transparency and supports explainability requirements. This aligns with Responsible AI principles and addresses legal implications. Enabling users to prove feedback on every response may overwhelm users and does not directly address the goal of ensuring content safety. Integrating Azure AI Foundry Content Safety APIs helps entify and filter harmful content in real-time, ensuring the safety and appropriateness of the model's outputs. Training the model exclusively on synthetic data may limit its ability to generate realistic and contextually appropriate responses, reducing its effectiveness.

[What is Content Safety - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/responsible-content-safety/2-what-is-content-safety)


[Azure AI Foundry - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/4-azure-ai-foundry)

Q:: =============================================

You plan to build an AI solution that will detect harmful content in company documents.
Which Azure AI Foundry Service should you include in the solution?

Select only one answer.

- Azure AI Search
- Bot Service
- Content Safety
- Document Intelligence
- Metrics Advisor

A:: =============================================

1. Content Safety

Content Safety is the only listed service that proves the ability to automatically flag content in text or images as harmful. Content Safety recognizes four distinct categories of objectionable content: Hate and fairness, sexual, violence, and self-harm.

[Harm categories in Azure AI Content Safety - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/content-safety/concepts/harm-categories?tabs=warning)

[What are Azure AI services? - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/what-are-ai-services)

Q:: =============================================

You are building a custom copilot based on Azure OpenAI.
You discover attempts to exploit the copilot by jailbreaking it through a User Prompt Injection Attack (UPIA).
You need to increase security to prevent the jailbreak attack.
Which Azure AI Foundry Service should you include in the solution?

Select only one answer.

- Content Safety
- Face
- Language
- Veo Indexer
- Vision

A:: =============================================

1. Content Safety

Content Safety jailbreak risk detection recognizes four different classes of jailbreak attacks: Attempt to change system rules, embedding a conversation mockup to confuse the model , role-play, and encoding attacks. These can be used in LLM-based applications to prevent jailbreak attacks. All the other services listed are designed for different purposes.

[Jailbreak risk detection in Azure AI Content Safety - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/content-safety/concepts/jailbreak-detection)

[What are Azure AI services? - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/what-are-ai-services)

Q:: =============================================

Your organization is developing an AI-powered e-learning platform that generates personalized educational content based on user inputs and reference documents. Concerns exist about generating inappropriate or misleading educational materials.
You need to ensure AI-generated educational content complies with academic standards and avos inappropriate material.
What should you implement to address these concerns?

Select only one answer.

- Enable Azure Translator.
- Implement Azure AI Foundry Content Safety.
- Train a custom model with additional datasets.
- Use Azure AI Services Text Analytics.

A:: =============================================

1. Implement Azure AI Foundry Content Safety.

Azure Content Safety is the most suitable solution because it analyzes user inputs and reference documents to detect and block harmful or policy-violating content, ensuring generated educational materials are safe and compliant. Azure AI Services Text Analytics evaluates sentiment but does not address content safety or compliance. Training a custom model improves content relevance but does not safeguard against inappropriate or misleading outputs. Azure Translator enhances accessibility through multilingual support but does not address the core issue of ensuring content safety and compliance.

[What is Content Safety - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/responsible-content-safety/2-what-is-content-safety)

Q:: =============================================

Your organization is implementing Azure AI Foundry Content Safety to moderate user-generated content on a social messaging platform.
You need to configure Foundry Content Safety to entify and restrict harmful text content, including profanities and hate speech, while allowing customization for specific patterns.
Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

- Configure harmful patterns using the Custom Categories API.
- Enable built-in blocklists in Content Safety Studio.
- Enable encryption at rest with customer-managed keys.
- Use the Analyze Image API for text analysis.

A:: =============================================

1. Configure harmful patterns using the Custom Categories API.
2. Enable built-in blocklists in Content Safety Studio.

Enabling built-in blocklists in Content Safety Studio is essential as it proves predefined terms to effectively flag harmful content such as profanities and hate speech. Configuring harmful patterns using the Custom Categories API allows for tailored moderation by defining specific patterns that align with organizational needs. Enabling encryption at rest with customer-managed keys enhances data security but does not contribute to the detection or restriction of harmful text content. Using the Analyze Image API focuses on image moderation and is not applicable to the task of moderating text content.

[Azure AI services - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)


[Use the Azure Document Intelligence Studio - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/9-form-recognizer-studio)

Q:: =============================================

You are building an app that will analyze resumes and remove names and addresses.
You need to configure the Azure AI Language Personally entifiable Information (PII) detection feature for the app.
Which categories should you specify in the request?

Select only one answer.

- Person, Address, and IP
- Person and Address only
- Person, PersonType, and Address

A:: =============================================

1. Person and Address only

Person and Address will detect names and addresses.
PersonType will also remove job roles. IP will also remove IP addresses.

[Entity categories recognized by Personally entifiable Information (detection) in Azure Cognitive Service for Language - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/personally-entifiable-information/concepts/entity-categories)

[Publish and use a Language Understanding app - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/publish-use-language-understand-app/)

Q:: =============================================

You are building an app that will flag documents that contain the names of staff members by using the Azure AI Language Personally entifiable Information (PII) detection feature.
You need to configure the PII detection feature.
Which category should you use?

Select only one answer.

- Age
- DateTime
- Person
- PhoneNumber

A:: =============================================

1. Person

The Person category detects names of people in the PII detection feature. The PhoneNumber category detects phone numbers, the age category detects people’s ages, and the DateTime detects dates and time values.

[Entity categories recognized by Personally entifiable Information (detection) in Azure Cognitive Service for Language - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/personally-entifiable-information/concepts/entity-categories)

[Publish and use a Language Understanding app - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/publish-use-language-understand-app/)

Q:: =============================================

You plan to build an app that will transcribe large quantities of audio files by using the Azure AI Speech service batch transcription feature.
You need to recommend a storage solution for the audio files. The solution must minimize development effort.
What should you recommend?

Select only one answer.

- Azure Cosmos DB
- Azure Data Lake Storage
- Azure SQL Database
- Azure Storage

A:: =============================================

1. Azure Storage

Azure Storage is the only storage prover that can be used by default for batch transcription.

[Create a batch transcription - Speech service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/batch-transcription-create?pivots=speech-cli)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

Q:: =============================================

You are building an app that will recognize the intent and entities of user utterances in real-time.
You need to implement the pattern matching intent recognition mechanism. The solution must only detect entities that you define in a catalog of phrases.
Which entity type should you use?

Select only one answer.

- the List entity using Fuzzy mode
- the List entity using Strict mode
- the prebuilt entity using Fuzzy mode
- the prebuilt entity using Strict mode
- the regex entity using Fuzzy mode
- the regex entity using Strict mode

A:: =============================================

1. the List entity using Strict mode

The List entity is made up of a list of phrases that will gue the engine on how to match the text. When an entity has an of type List and is in Strict mode, the engine will only match if the text in the slot appears in the list.

[Pattern Matching overview - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/pattern-matching-overview#types-of-entities)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

Q:: =============================================

You are building a custom translation model.
You need to evaluate the precision of the text that you translated by using a Bilingual Evaluation Understudy (BLEU) score.
Which scale is used for the score?

Select only one answer.

- between 0 and 1
- between 0 and 100
- low, medium, and high

A:: =============================================

1. between 0 and 100

A BLEU score is a number between zero and 100. A score of zero indicates a low-quality translation, where nothing in the translation matches the reference. A score of 100 indicates a perfect translation that is entical to the reference. It is unnecessary to attain a score of 100. A BLEU score between 40 and 60 indicates a high-quality translation.

[Custom Translator for beginners - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/custom-translator/beginners-gue#what-is-a-bleu-score)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

Q:: =============================================

You are building a model that uses Conversational Language Understanding (CLU).
You need to measure how accurate the model is by using the ratio between the correctly entified positives (true positives) and all entified positives.
Which metric should you use?

Select only one answer.

- Bilingual Evaluation Understudy (BLEU)
- F1 score
- precision
- recall

A:: =============================================

1. precision

Precision measures how precise/accurate a model is. It is the ratio between the correctly entified positives (true positives) and all entified positives. The precision metric reveals how many of the predicted classes are correctly labeled.
Recall measures the model's ability to predict actual positive classes. F1 score is a function of precision and recall. BLEU is from the Azure AI Translator service.

[Conversational Language Understanding evaluation metrics - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/conversational-language-understanding/concepts/evaluation-metrics)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

Q:: =============================================

You plan to build a chatbot that will help users answer FAQs.
You need to entify which scenarios are suitable for use with the Azure AI Language question answering service.
Which three scenarios should you entify? Each correct answer presents a complete solution.

Select all answers that apply.

- when you have a bot conversation that includes dynamic information
- when you have a bot conversation that includes static information
- when you have dynamic information in a knowledge base of answers
- when you have static information in a knowledge base of answers
- when you need to prove the same answer to a request, question, or command
- when you need to prove unique answers to each request, question, or command

A:: =============================================

1. when you have a bot conversation that includes static information
2. when you have static information in a knowledge base of answers
3. when you need to prove the same answer to a request, question, or command

Question answering only works with static information, not with dynamic information. In addition, it will always prove the same answer to the same question.

[What is question answering? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/overview)

[Build a question answering solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

Q:: =============================================

You are building a solution that uses the Azure AI Language question answering service.
You need to import FAQ documents for the solution.
Which types of data will be extracted during the import process?

Select only one answer.

- formatted text, URLs, and bulleted and numbered lists only
- formatted text, URLs, images, and diagrams only
- unformatted text, images, and diagrams only
- unformatted text, numbered lists, and unstructured data only

A:: =============================================

1. formatted text, URLs, and bulleted and numbered lists only

Currently, the extraction of images within documents that are uploaded to question answering for extraction is unsupported, as images need to be reachable via a public URL.

[Import document format guelines - question answering - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/reference/document-format-guelines)

[Build a question answering solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

Q:: =============================================

You need to build an app that will use Azure AI Vision to analyze and detect animals in images.
Which type of project should you use?

Select only one answer.

- image classification
- image detection
- object analysis
- object classification
- object detection

A:: =============================================

1. object detection

Object detection returns the coordinates in an image where the applied label(s) can be found, while image classification applies one or more labels to an entire image.

[What is Custom Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/overview)

[Detect objects in images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-objects-images/)

Q:: =============================================

You are developing a custom vision model using Microsoft Azure AI Custom Vision to detect specific objects in images. The dataset includes labeled images for training and valation.
You need to ensure that the trained model meets the required accuracy by assessing its performance.
What action should you take?

Select only one answer.

- Deploy the model without testing.
- Evaluate precision and recall metrics.
- Source new images for testing.
- Retrain the model with a new dataset.

A:: =============================================

1. Evaluate precision and recall metrics.

Evaluating precision and recall metrics is the most effective way to assess the performance of an object detection model, as these metrics prove a detailed understanding of its accuracy and ability to entify objects correctly. Deploying the model without testing bypasses the critical step of ensuring its reliability and effectiveness. Sourcing new images for testing isn't necessary with a dataset already containing valation images. Retraining the model with a new dataset focuses on improving data quality rather than assessing the current model's performance, making it unsuitable for the given objective.

[Test and retrain a Custom Vision model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/test-your-model)

Q:: =============================================

You are building an app that will be deployed to an edge device and will use Azure AI Custom Vision to analyze images of fruits.
You need to select a model domain for the app. The solution must support running the app without internet connectivity.
Which model should you use?

Select only one answer.

- Compact domain
- Food domain
- General
[A1] domain
- General 
[A2] domain

A:: =============================================

1. Compact domain

Only Compact domain is correct. The Azure AI Custom Vision service only exports compact domains, and the models generated by compact domains are optimized for the constraints of real-time classification on mobile devices.

[Select a domain for a Custom Vision project - Computer Vision - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/select-domain)

[Export your model to mobile - Custom Vision Service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/export-your-model)

[Classify images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/classify-images/)

Q:: =============================================

You are building an app that uses Azure AI Veo Indexer.
You need to extract keyframes from uploaded veo and store them on a disk by using the API.
How should you implement the solution?

Select only one answer.

- Upload the veo and download the ZIP file of the thumbnails.
- Upload the veo, download the ZIP file of the thumbnails, and get the thumbnail for each keyframe.
- Upload the veo, get the veo index, and get the thumbnail for each keyframe.

A:: =============================================

1. Upload the veo, get the veo index, and get the thumbnail for each keyframe.

You need to upload the veo, get the veo index, and get the thumbnail for each keyframe. Three API calls need to be done.
Uploading the veo and then downloading the ZIP file of the thumbnails is the path through the Azure portal. You need the index to know the correct parameters for the thumbnail request.

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/analyze-veo/)

Q:: =============================================

You are building a solution that uses Azure AI Search.
You need to create a skillset definition.
What are minimum sections you should include in the definition?

Select only one answer.

- `name`, `description`, and `skills`
- `name, description, knowledgeStore`, and `encryptionKey`
- `name, description, skills`, and `cognitiveServices `
- `name, description, skills, knowledgeStore`, and `encryptionKey`

A:: =============================================

1. `name`, `description`, and `skills`

Only `name`, `description`, and `skills` are required.
`cognitiveServices` is used for billable skills that call Cognitive Services APIs.
`knowledgeStore` specifies an Azure Storage account and the settings for projecting the skillset output into tables, blobs, and files in Azure Storage.
`encryptionKey` specifies an Azure key vault and customer-managed keys used to encrypt sensitive content (descriptions, connection strings, keys) in a skillset definition.

[Create a skillset - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-defining-skillset#add-a-skillset-definition)

[Create a custom skill for Azure Cognitive Search - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-enrichment-pipeline-azure-cognitive-search/)

Q:: =============================================

You have a web app named App1 that performs customs searches.
You are building a solution that uses Azure AI Search.
You need to include App1 as a custom skill as part of the solution.
Which @odata.type should you use to call App1?

Select only one answer.

- `Microsoft.Skills.Custom.AmlSkill`
- `Microsoft.Skills.Custom.WebApiSkill`
- `Microsoft.Skills.Text.CustomEntityLookupSkill `
- `Microsoft.Skills.Util.ConditionalSkill`

A:: =============================================

1. `Microsoft.Skills.Custom.WebApiSkill`

`Microsoft.Skills.Custom.WebApiSkill` allows the extensibility of an AI enrichment pipeline by making an HTTP call to a custom web API.

[Built-in skills - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-predefined-skills)

[Create a custom skill for Azure Cognitive Search - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-enrichment-pipeline-azure-cognitive-search/)

Q:: =============================================

You are building a knowledge mining solution that uses Azure AI Search.
You need to apply AI enrichment to your indexer pipeline to generate links to Wikipedia articles.
Which skill should you use?

Select only one answer.

- `Microsoft.Skills.Custom.WebApiSkill`
- `Microsoft.Skills.Text.KeyPhraseExtractionSkill `
- `Microsoft.Skills.Text.PIetectionSkill`
- `Microsoft.Skills.Text.V3.EntityLinkingSkill`

A:: =============================================

1. `Microsoft.Skills.Text.V3.EntityLinkingSkill`

`Microsoft.Skills.Text.V3.EntityLinkingSkill` uses a pretrained model to generate links for recognized entities to articles in Wikipedia.

[Built-in skills – Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-predefined-skills)

[Create an Azure Cognitive Search solution – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are building a knowledge mining solution that uses Azure AI Search.
You need to extract content from a file within the enrichment pipeline by using AI enrichment.
Which built-in skill should you use?

Select only one answer.

- `Microsoft.Skills.Text.KeyPhraseExtractionSkill`
- `Microsoft.Skills.Text.SplitSkill `
- `Microsoft.Skills.Text.V3.EntityRecognitionSkill `
- `Microsoft.Skills.Util.DocumentExtractionSkill`

A:: =============================================

1. `Microsoft.Skills.Util.DocumentExtractionSkill`

`Microsoft.Skills.Util.DocumentExtractionSkill` is the built-in skill used to extract content from a file within the enrichment pipeline.

[Built-in skills – Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/cognitive-search-predefined-skills)

[Create an Azure Cognitive Search solution – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

Your company processes various forms, including health insurance cards and entity documents, and requires accurate extraction of specific fields.
You need to recommend a solution for extracting structured data from these forms.
What should you do?

Select only one answer.

- Train a composed model.
- Use Azure OCR.
- Use prebuilt models for Health Insurance Card and Document.
- Use the Layout model.

A:: =============================================

1. Use prebuilt models for Health Insurance Card and Document.

Prebuilt models for Health Insurance Card and Document in Microsoft Azure AI Document Intelligence are the optimal choice for extracting structured data from these forms because they are specifically designed for this purpose, ensuring accuracy and efficiency. Training a composed model introduces unnecessary complexity when prebuilt models are available for these document types. Azure OCR focuses on text extraction without contextual understanding, making it unsuitable for structured data extraction. The Layout model supports key-value pair extraction but lacks the specificity required for extracting specific fields from health insurance cards and entity documents.

[Understand AI Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/2-understand)


[Get started with Azure Document Intelligence](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)

Q:: =============================================

Your company receives multi-page PDF documents from clients containing specifications and statements of work, often including tables and selection marks.
You need to extract text, tables, and selection marks while maintaining the document's structure.
What should you recommend?

Select only one answer.

- Azure AI Vision OCR (Optical Character Recognition)
- Azure Document Intelligence general model
- Azure Document Intelligence layout model
- Azure Document Intelligence read model

A:: =============================================

1. Azure Document Intelligence layout model

Azure Document Intelligence layout model is the most appropriate solution because it is specifically designed to extract text, tables, and selection marks while preserving the document's structure, which is essential for processing multi-page PDF documents. Azure AI Vision OCR is limited to text extraction from images and does not support advanced features like table or selection mark recognition. The general model supports entity extraction but does not focus on maintaining the document's structure. The read model is limited to extracting printed and handwritten text and does not include the advanced capabilities required for this scenario.

[What is Azure Document Intelligence? - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/2-what-form-recognizer)


[Use the General Document, Read, and Layout models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/3-use-general-document-read-layout-models)

Q:: =============================================

Your company receives customer feedback in audio format, including conversations between agents and customers.
You need to perform transcription, sentiment analysis, and generate summaries from these recordings.
What service should you recommend?

Select only one answer.

- Azure AI Content Understanding
- Azure AI Speech
- Azure AI Language
- Azure AI Document Intelligence

A:: =============================================

1. Azure AI Content Understanding

Azure AI Content Understanding is the most suitable solution as it offers transcription, sentiment classification, and summary generation capabilities for audio recordings, addressing all requirements of the scenario. Azure AI Document Intelligence is not appropriate because it processes text-based documents and lacks audio-related functionalities. Azure AI Language offers sentiment analysis and summaries but is unable to transcribe audio. Azure AI Speech can transcribe the audio but lacks other required functionality.

[Create a multimodal analysis solution with Azure AI Content Understanding - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/)

Q:: =============================================

You are building an app that will analyze the sentiment of user feedback by using Azure AI Language.
You have a test document named Test.docx that contains one positive sentence and multiple neutral sentences.
You need to valate the app by analyzing Test.docx.
Which label will the app return for Test.docx?

Select only one answer.

- mixed
- negative
- neutral
- positive

A:: =============================================

1. positive

If there is at least one positive sentence in the document, and the rest of the document is neutral, then the document label is positive.

[How to perform sentiment analysis and opinion mining - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/sentiment-opinion-mining/how-to/call-api)

[Extract insights from text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

Q:: =============================================

You are building a custom translation model.
You need to use bilingual training documents to teach the model your terminology and style.
Which rule should you follow?

Select only one answer.

- Be liberal.
- Be restrictive.
- Be strict.

A:: =============================================

1. Be liberal.

Be liberal is correct. Any in-domain human translation is better than machine translation. Add and remove documents as you go and try to improve the Bilingual Evaluation Understudy (BLEU) score.
Be strict is incorrect. Compose them to be optimally representative of what you are going to translate in the future. Be restrictive is also incorrect. A phrase dictionary is case-sensitive, and any word or phrase listed is translated in the way you specify. In many cases, it is better to not use a phrase dictionary and let the system learn.

[Custom Translator for beginners - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/custom-translator/beginners-gue#what-should-i-use-for-training-material)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

Q:: =============================================

You are building an orchestration workflow to orchestrate and connect multiple Language Understanding models and question answering projects for use in a bot.
Which two operations can you perform in an orchestration workflow based on Azure AI Language service? Each correct answer presents a complete solution.

Select all answers that apply.

- Add entities to your orchestration workflow directly.
- Connect to Language Understanding applications that are owned by the same resource as the orchestration workflow.
- Connect to question answering projects that are in the same Azure AI Language service resource as your orchestration workflow.
- Label a single word as two different entities.

A:: =============================================

1. Connect to Language Understanding applications that are owned by the same resource as the orchestration workflow.
2. Connect to question answering projects that are in the same Azure AI Language service resource as your orchestration workflow.

Adding entities to your orchestration workflow is not allowed. Entities are mutually exclusive within an orchestration workflow.

[Frequently Asked Questions for orchestration projects - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/orchestration-workflow/faq)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

Q:: =============================================

You are building a chatbot that will use the Azure AI Language question answering service.
You need to entify the operational costs for the service.
Which two parameters will influence the costs? Each correct answer presents a complete solution.

Select all answers that apply.

- the number of assigned metadata tags
- the number of knowledge base editors
- the number of supported languages
- the required throughput
- the size and the number of knowledge bases

A:: =============================================

1. the required throughput
2. the size and the number of knowledge bases

The throughput, the size, and the number of knowledge bases affect the pricing tier, whereas the other parameters do not affect pricing.

[Azure resources – question answering – Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/concepts/azure-resources)

[Build a question answering solution – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

Q:: =============================================

You are building an app that will extract specific information from scanned receipts.
Which service should you use?

Select only one answer.

- Azure Application Insights
- Azure AI Language
- Azure AI Document Intelligence
- Azure AI Metrics Advisor

A:: =============================================

1. Azure AI Document Intelligence

Azure AI Document Intelligence is capable of automatically extracting information from given documents by using machine learning.
Azure AI Metrics Advisor, Azure Application Insights, and Azure AI Language do not allow you to extract specific data from scanned receipts.

[Use prebuilt Form Recognizer models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/use-prebuilt-form-recognizer-models/)

Q:: =============================================

You are building an app that will extract insights from veo files.
You need to entify which service to use. The solution must ensure that you can customize the language model used.
What should you use?

Select only one answer.

- Azure AI Language
- Azure Communication Services
- Azure AI Vision
- Azure AI Veo Indexer

A:: =============================================

1. Azure AI Veo Indexer

The only service that can customize the language model for a solution based on gaining insights from veos in Azure AI Veo Indexer.

[Customize a Language model in Azure Veo Indexer - Azure - Azure Veo Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-veo-indexer/customize-language-model-overview)

[Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

Q:: =============================================

You are building an Azure AI Language solution.
You need to deploy the solution to a location without internet connectivity.
What should you do?

Select only one answer.

- Deploy the solution to a Docker host container.
- Download the model and deploy it to a virtual machine.
- Use an Azure AI Foundry Service standard instance.

A:: =============================================

1. Deploy the solution to a Docker host container.

You can use disconnected containers to host Language Understanding on-premises.
There is no virtual machine set up to run a Language Understanding instance and a standard instance still has Language Understanding running in the cloud.

[Use Docker containers in disconnected environments - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/containers/disconnected-containers)

[Deploy cognitive services in containers - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/investigate-container-for-use-cognitive-services/)

Q:: =============================================

You plan to build an app that will use Azure AI Foundry Service.
You need to entify the methods that can be used to authenticate to Azure AI Services.
Which two methods can you use? Each correct answer presents a complete solution.

Select all answers that apply.

- a SAML token
- a subscription key
- Microsoft Entra - Kerberos

A:: =============================================

1. a subscription key
2. Microsoft Entra You can use a single or multi-service subscription keys to authenticate to Azure AI Services. You can also authenticate to Azure AI Services by using a Microsoft Entra service principal and role-based access control (RBAC).
Azure AI Services do not support authentication by using SAML tokens or Kerberos.

[Authentication in Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/authentication?tabs=powershell#authenticate-with-an-access-token)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

Q:: =============================================

You are building an app that will use Azure AI Custom Vision. The app will be deployed to an internet host.
You enable firewall rules for your Azure AI Services account.
You need to ensure that the app can access the Azure AI Custom Vision service over the internet.
What should you do?

Select only one answer.

- Assign a role-based access control (RBAC) role to the Azure AI Custom Vision service.
- Grant access to a specific virtual network.
- Grant access to an internet IP range.
- Include an access token in the Authorization header.

A:: =============================================

1. Grant access to an internet IP range.

If you enable the firewall for the Azure AI Services account, you need to allow network access to the service. You can achieve this by either allowing access from a specific virtual network or adding an IP range to the firewall rules. In this situation, the app is deployed to the internet, and you can prove specific internet hosts access by adding an IP or range of IPs to the firewall rules.

[Configure Virtual Networks for Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/cognitive-services-virtual-networks?context=%2Fazure%2Fcognitive-services%2Flanguage-service%2Fcontext%2Fcontext&tabs=portal)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

Q:: =============================================

You have an Azure AI Foundry Service resource.
You need to enable diagnostic logging.
What are two prerequisites for diagnostic logging? Each correct answer presents a complete solution.

Select all answers that apply.

- a Log Analytics workspace
- an Azure Cosmos DB for NoSQL account
- an Azure key vault
- an Azure SQL database
- an Azure Storage account

A:: =============================================

1. a Log Analytics workspace
2. an Azure Storage account

The prerequisites to enable diagnostic logging are to have an Azure Storage resource that retains diagnostic logs for policy audit, static analysis, or backup. A Log Analytics resource proves a flexible log search and analytics tool that allows for analysis of raw logs generated by an Azure resource.

[Diagnostic logging - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/diagnostic-logging)

[Monitor Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/monitor-cognitive-services/)

Q:: =============================================

You are developing a containerized optical character recognition (OCR)-capable application by using Azure AI Services containers.
While developing the solution, you retrieve a status message of “Mismatch”, and the connection to the AI Services resource fails.
You need to ensure that the solution can connect to the AI Services resource.
What should you do?

Select only one answer.

- Confirm that the API key is for the correct region.
- Confirm that the API key is for the correct resource type.
- Confirm that the Azure AI Services resource is online.
- Upgrade the Azure AI Services resource to a higher tier.

A:: =============================================

1. Confirm that the API key is for the correct resource type.

Mismatch means that the wrong API key has been used. If you have proved an API key or endpoint for a different kind of Azure AI Services resource, you find your API key and service region in the Azure portal, in the Keys and Endpoint section for your Azure AI Services resource.
If the API key is inval, you must confirm that the API key is for the correct region. If the API key has exceeded the quota, then you can either upgrade your pricing tier or wait for an additional quota to become available. Find your tier in the Azure portal, in the Pricing Tier section of your Azure AI Service resource. The mismatch error would not be generated if the resource was offline.

[Cognitive Services containers FAQ - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/containers/container-faq)

[Deploy cognitive services in containers - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/investigate-container-for-use-cognitive-services/)

Q:: =============================================

You have a website that enables users to upload and share PNG image files.
You implement an Azure AI Foundry Content Safety solution for the website.
The users report that some images fail to display after they are uploaded.
You need to ensure that the solution assigns proper content flags to the uploaded images.
What should you do?

Select only one answer.

- Adjust the content categories to be used.
- Adjust the severity level.
- Convert the images to a different file format.
- Remove the severity level.

A:: =============================================

1. Adjust the severity level.

Best practices for improving system performance:

- Monitor the system's performance regularly to ensure that the tradeoff is appropriate for your use case.

- Modify the severity levels for blocking based on user feedback and observed trends in content safety.


[Transparency Note and use cases for AI Content Safety - Azure AI services | Microsoft Learn](https://learn.microsoft.com/legal/cognitive-services/content-safety/transparency-note?context=%2Fazure%2Fai-services%2Fcontent-safety%2Fcontext%2Fcontext)

Q:: =============================================

Your team is deploying an AI agent to perform actions based on user requests, such as scheduling meetings and sending notifications.
You need to integrate the AI agent with tools that enable it to perform these actions programmatically.
What should you do?

Select only one answer.

- Add custom functions.
- Configure static templates.
- Enable default model capabilities.
- Use a pre-trained chatbot framework.

A:: =============================================

1. Add custom functions.

Adding custom functions enables the AI agent to dynamically execute specific actions such as scheduling meetings and sending notifications, making it the most suitable choice for the scenario. Configuring static templates does not prove the flexibility needed for dynamic action execution, limiting its effectiveness. Default model capabilities lack the ability to perform specific programmatic actions, making them insufficient for the task. Using a pre-trained chatbot framework without customization fails to address the specific requirements for executing actions programmatically, reducing its applicability in this context.

[Integrate custom tools into your agent - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/)

Q:: =============================================

Your organization plans to develop an AI solution using Microsoft Azure AI Foundry Agent Service to automate customer support workflows.
You need to configure the agent to interact with external data sources and execute actions based on user queries.
Each correct answer presents part of the solution. Which two actions should you perform?

Select all answers that apply.

- Add Bing search tools in the agent configuration.
- Configure Azure Functions in the agent configuration file.
- Deploy a containerized image.
- Set up a SQL database.
- Use Computer Vision.

A:: =============================================

1. Add Bing search tools in the agent configuration.
2. Configure Azure Functions in the agent configuration file.

Adding Bing search tools enables the agent to retrieve relevant information from external sources, enhancing its ability to respond accurately to user queries. Configuring Azure Functions allows the agent to execute specific actions programmatically, which is crucial for automating workflows based on user inputs. Deploying a containerized image is not necessary to configure the agent's capabilities. Setting up a SQL database is not required for configuring the agent's interaction capabilities, as it does not directly contribute to the goal of automating customer support workflows. Using Computer Vision is unrelated to the task of configuring the agent for customer support workflows, as it focuses on image analysis rather than interaction with external data sources.

[Develop an AI agent with Azure AI Foundry Agent Service - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-azure/)

Q:: =============================================

Your organization is using Azure AI Foundry Agent Service to automate customer support workflows.
You need to configure an agent to interact with external APIs and use real-time data for responses.
Each correct answer presents part of the solution. Which three actions should you perform?

Select all answers that apply.

- Define tools for API access.
- Deploy the agent using Azure SDK.
- Manually parse API responses in code.
- Configure the Bing Search tool.
- Set up an Azure AI Search resource.
- Use Blob Storage for conversation state.

A:: =============================================

1. Define tools for API access.
2. Deploy the agent using Azure SDK.
3. Configure the Bing Search tool.

Defining tools for API access ensures the agent can interact with external APIs effectively. Deploying the agent using Azure SDK makes it operational within the Azure environment, enabling API interactions. Configuring the Bing Search tool enables the agent to access real-time data. Setting up an Azure AI Search resource is optional and does not directly contribute to enabling API interaction for the agent. Manually parsing API responses is unnecessary because Azure AI Foundry Agent Service automates tool calling and response handling. Using Blob Storage for conversation state is unnecessary because Azure AI Foundry Agent Service manages conversation state through threads.

[Develop an AI agent with Azure AI Foundry Agent Service - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-azure/)

Q:: =============================================

You have an Azure OpenAI in Foundry Models solution. The solution uses a specific GPT-35-Turbo model version that was current during initial deployment. Auto-update is disabled.
Sometime later, you investigate the deployed solution and discover that it uses a newer version of the model.
Why was the model version updated?

Select only one answer.

- Auto-update is always enabled.
- Auto-update is enabled automatically when a new version is released.
- Model versions are updated automatically when the version is older than five version updates.
- The model version reached its retirement date.

A:: =============================================

1. The model version reached its retirement date.

As your use of Azure OpenAI evolves, and you start to build and integrate with applications, you might want to manually control model updates so that you can first test and valate whether model performance remains consistent for a use case before performing an upgrade.
When you select a specific model version for a deployment, this version will remain selected until you either choose to manually update it, or once you reach the retirement date of the model. When the retirement date is reached, the model will upgrade to the default version automatically at the time of retirement.

[Azure OpenAI Service working with models - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/how-to/working-with-models?tabs=powershell)

Q:: =============================================

You are creating an application that references the Azure OpenAI REST API for a DALL-E model.
You plan to use thumbnails of the images that DALL-E generates and display them in a table on a webpage.
You need to find the image URLs in the JSON response.
Which element should you review?

Select only one answer.

- the s array element
- the images array element
- the imageURL array element
- the result element

A:: =============================================

1. the result element

The result from the initial request does not immediately return the results of the image generation process. Instead, the response includes an **operation-location** header with a URL for a callback service that your application code can poll until the results of the image generation are ready. The **result** element includes a collection of **url** elements, each of which references a PNG image file generated from the prompt.

[Use the Azure OpenAI REST API to consume DALL-E models - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/generate-images-azure-openai/4-dall-e-rest-api)

Q:: =============================================

You are building a GPT-based chat application that will answer questions about your company.
You plan to use the Using your data feature in Azure OpenAI to ground the model with your company data.
While testing, you discover that some responses are not accurate enough.
You need to configure the Azure OpenAI resource to filter out less-relevant documents for responses.
Which parameter should you configure?

Select only one answer.

- Content data
- File name
- Retrieved documents
- Strictness

A:: =============================================

1. Strictness

The Strictness parameter sets the threshold to categorize documents as relevant to your queries. Raising the Strictness parameter value means a higher threshold for relevance and filters out more less-relevant documents for responses. Retrieved documents specifies the number of top-scoring documents from your data index used to generate responses. Content data specifies the fields in your index that contain the main text content of each document. File name specifies the field in your index that contains the original file name of each document.

[Using your data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/use-your-data?tabs=ai-search)

Q:: =============================================

You are building a GPT-based chat application that will answer questions about your company.
You plan to test the application by using strategies defined by Microsoft best practices.
Which three prompt engineering strategies should you conser while testing the application? Each correct answer presents a complete solution.

Select all answers that apply.

- Be Descriptive
- Be minimalistic
- Be simple
- Be Specific
- Order Matters

A:: =============================================

1. Be Descriptive
2. Be Specific
3. Order Matters

Be Specific means to leave as little to interpretation as possible. Be Descriptive means to use analogies. Order Matters means that the order in which you present information to the model can affect the output. Therefore, those three are valbest practices. Be simple and be minimalistic do not produce the best results and are, therefore, not best practices

[Azure OpenAI Service - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/prompt-engineering)

Q:: =============================================

Your organization is developing a customer-facing application that uses Azure OpenAI in Foundry Models to generate personalized responses. The application is connected to a Microsoft Azure AI Search index.
You need to configure the application to retrieve relevant data from the search index.
What should you do?

Select only one answer.

- Deploy an additional Azure OpenAI model.
- Enable semantic search.
- Increase chunk size for data ingestion.
- Use keyword search.

A:: =============================================

1. Enable semantic search.

Enabling semantic search enhances the precision and relevance of search results by interpreting the meaning behind query terms, making it the most suitable solution for improving response accuracy in this scenario. Increasing chunk size impacts data processing but does not directly affect the accuracy of retrieved data. Deploying an additional Azure OpenAI model does not address the specific need for improving data retrieval accuracy from the search index. Using keyword search lacks semantic capabilities, which are essential for achieving the desired level of accuracy.

[Make your data searchable - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/3-search-data)

Q:: =============================================

Your company uses Azure OpenAI in Foundry Models to analyze large datasets.
You need to configure the application to retrieve relevant data efficiently.
What action should you take?

Select only one answer.

- Deploy a GPT-4 model.
- Enable vector search.
- Increase chunk size.
- Use keyword-based search.

A:: =============================================

1. Enable vector search.

Enabling vector search enhances the relevance and efficiency of data retrieval, meeting the stated goal. Deploying an additional model does not address the need for efficient data retrieval, making it unsuitable. Increasing chunk size affects data processing but does not directly improve retrieval efficiency. Using keyword-based search lacks semantic capabilities, which are critical for achieving the desired outcome.

[Make your data searchable - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/3-search-data)


[Azure OpenAI On Your Data - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/use-your-data?tabs=ai-search%2Ccopilot)

Q:: =============================================

You are deploying a generative AI solution using an Azure OpenAI in Foundry Models service to process customer feedback and generate summaries.
You need to optimize the solution for performance and ensure its responses align with the organization's tone and style.
Each correct answer presents part of the solution. Which three actions should you perform?

Select all answers that apply.

- Deploy the model on edge devices.
- Enable support for multiple languages.
- Fine-tune the model with customer feedback data.
- Set up monitoring in Azure to track response accuracy and resource usage.
- Use prompt engineering to refine the model's output.

A:: =============================================

1. Fine-tune the model with customer feedback data.
2. Set up monitoring in Azure to track response accuracy and resource usage.
3. Use prompt engineering to refine the model's output.

To optimize the generative AI solution for performance and ensure its responses align with the organization's tone and style, it is essential to set up monitoring in Azure to continuously evaluate the model's performance and resource usage. Fine-tuning the model with customer feedback data customizes the solution to meet specific organizational requirements, ensuring alignment with tone and style. Additionally, using prompt engineering refines the model's responses by structuring input effectively, enhancing the quality and relevance of the generated content. Deploying the model on edge devices and enabling support for multiple languages do not directly address the stated goals, as they focus on deployment strategy and additional features rather than performance optimization or alignment with tone and style.

[Fine-tune a language model with Azure AI Foundry - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/finetune-model-copilot-ai-studio/)

Q:: =============================================

Your company is integrating Azure OpenAI in Foundry Models into its internal knowledge base system to prove intelligent query responses.
You need to ensure that the most relevant documents are prioritized during data retrieval.
What should you do?

Select only one answer.

- Enable hybrsearch mode.
- Increase retrieved document count.
- Reduce chunk size.
- Set strictness to a higher value.

A:: =============================================

1. Set strictness to a higher value.

Setting strictness to a higher value ensures that only the most relevant documents are retrieved, effectively prioritizing relevance during data retrieval. Enabling hybrsearch mode combines different search methods but does not specifically focus on document relevance. Increasing the number of retrieved documents may include less relevant data, which contradicts the goal of prioritizing relevance. Reducing chunk size impacts data granularity but does not directly influence the prioritization of document relevance.

[Azure OpenAI On Your Data - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/use-your-data?tabs=ai-search%2Ccopilot)

Q:: =============================================

Your organization plans to implement a generative AI solution to assist the customer success by summarizing customer complaints and questions.
You need to ensure the model proves accurate summaries while reducing costs.
What action should you take?

Select only one answer.

- Apply prompt engineering without external data sources.
- Deploy a model without grounding data and rely on pre-trained capabilities.
- Fine-tune a model using customer query data without an orchestration layer.
- Use Retrieval-Augmented Generation (RAG) with Azure AI Search for grounding data.

A:: =============================================

1. Use Retrieval-Augmented Generation (RAG) with Azure AI Search for grounding data.

Using Retrieval-Augmented Generation (RAG) with Azure AI Search ensures the model proves accurate and contextually relevant summaries by incorporating domain-specific data. Deploying a model without grounding data relies solely on pre-trained capabilities, resulting in less accurate outputs. Fine-tuning a model without an orchestration layer fails to dynamically integrate real-time contextual data, limiting its effectiveness, and is significantly more expensive. Applying prompt engineering without external data sources improves response quality but does not address the need for domain-specific grounding.

[Understand how to ground your language model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/2-ground-language-model)

Q:: =============================================

Your organization scans and stores various document types, such as invoices, receipts, and custom forms, in PDF format.
You need to extract structured information from these documents for analysis.
Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

- Convert the documents into plain text.
- Train a custom model using labeled datasets in Azure AI Document Intelligence.
- Use the General Document model in Azure AI Document Intelligence.
- Use the Layout model in Azure AI Document Intelligence.
- Use the prebuilt Invoice model in Azure AI Document Intelligence.

A:: =============================================

1. Train a custom model using labeled datasets in Azure AI Document Intelligence.
2. Use the prebuilt Invoice model in Azure AI Document Intelligence.

Converting the documents into plain text results in the loss of structural information, which is essential for extracting meaningful data. Training a custom model using labeled datasets in Azure AI Document Intelligence enables accurate extraction of data from unique forms that do not conform to standard templates. The General Document model is deprecated and not recommended for use in new solutions, making it unsuitable for this task. The Layout model can extract text and structure but is not optimized for specific document types like invoices or receipts, which limits its effectiveness for this scenario. The prebuilt Invoice model in Azure AI Document Intelligence is specifically designed to extract key information from invoices, making it an appropriate choice for this task.

[Get started with Azure Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)


[Choose a model type - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/4-choose-model-type)

Q:: =============================================

You are using Azure AI Translator to translate documents from one language to another.
You need to extend the capabilities of an application by using the Azure AI Translator service.
Which three features are available in the Translator service? Each correct answer presents a complete solution.

Select all answers that apply.

- Detect language
- Dictionary lookup
- Entity extraction
- Intent recognition
- Transliterate

A:: =============================================

1. Detect language
2. Dictionary lookup
3. Transliterate

Apart from translation, the following features are part of Translator: Transliterate, Detect, Dictionary lookup, and Dictionary example.

[What is Microsoft Azure Cognitive Services Text Translation? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/text-translation-overview)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

Q:: =============================================

You are building an Azure AI Translator custom model.
You need to ensure that the translation accuracy for the model has a Bilingual Evaluation Understudy (BLEU) score that indicates high quality.
What is the minimum score range required?

Select only one answer.

- 0 to 19
- 20 to 39
- 40 to 59
- 60 to 79
- 80 to 100

A:: =============================================

1. 40 to 59

between 40 and 60 indicates a high-quality translation..

[Key terms - Custom Translator - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/custom-translator/key-terms)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

Q:: =============================================

You are building an app that will analyze meeting recordings and entify who is speaking at which moment in time.
You need to configure a voice profile for the app.
Which type of voice profile should you use?

Select only one answer.

- Speaker entification
- text-dependent verification
- text-independent verification

A:: =============================================

1. Speaker entification

Text-independent verification means that speakers can speak in everyday language in enrollment and verification phases.
Text-dependent verification means that speakers need to choose the same passphrase to use during both enrollment and verification phases. This is the voice profile that should be used when configuring a voice profile for the app.
Speaker entification helps you determine an unknown speaker’s entity within a group of enrolled speakers.

[Speaker recognition overview - Speech service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/speaker-recognition-overview)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

Q:: =============================================

You are building an app that will enable users to create notes by using speech.
You need to recommend the Azure AI Speech service model to use. The solution must support noisy environments.
Which model should you recommend?

Select only one answer.

- base
- base with customizations
- custom speech-to-text
- default

A:: =============================================

1. custom speech-to-text

The custom speech-to-text model is correct, as you need to adapt the model because a factory floor might have ambient noise, which the model should be trained on.

[Speech-to-text FAQ - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/faq-stt)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

Q:: =============================================

Your organization has trained a custom vision model using Microsoft Azure Custom Vision to classify product images. The model has satisfactory performance metrics.
You need to make the model available for predictions in a production environment.
What should you do next?

Select only one answer.

- Create a new Azure resource for the model.
- Export the model for local use.
- Publish the model and retrieve its Prediction URL and key.
- Re-train the model with additional data.

A:: =============================================

1. Publish the model and retrieve its Prediction URL and key.

Publishing the trained iteration and retrieving its Prediction URL and key is the appropriate action to make the model accessible for programmatic predictions in a production environment. Exporting the model for local use is not aligned with the goal of leveraging the Microsoft Azure Custom Vision Prediction API. Re-training the model is unnecessary as the current performance metrics are satisfactory and does not contribute to the deployment process. Creating a new Azure resource is unrelated to the task of deploying the trained model and does not address the stated goal.

[Get started with Azure Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/3-get-started)


[Create a client application that uses an image generation model - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/4-dall-e-rest-api)

Q:: =============================================

You are developing a custom vision model using Microsoft Custom Vision to classify images of various plant species. A subset of the dataset has already been labeled, and an initial iteration of the model has been trained.
You need to efficiently improve the model's accuracy by optimizing the labeling process for the remaining untagged images.
Each correct answer presents part of the solution. Which three actions should you perform?

Select all answers that apply.

- Delete all previously tagged images.
- Manually label all images from scratch.
- Prioritize reviewing tags with high prediction uncertainty.
- Review and confirm suggested tags for each image.
- Train the model without reviewing tags.
- Use Smart Labeler to suggest tags for untagged images.

A:: =============================================

1. Prioritize reviewing tags with high prediction uncertainty.
2. Review and confirm suggested tags for each image.
3. Use Smart Labeler to suggest tags for untagged images.

To optimize the labeling process and improve the model's accuracy, it is essential to review and confirm suggested tags to ensure data reliability. Prioritizing tags with high prediction uncertainty helps address ambiguous cases effectively, while using the Smart Labeler streamlines the process by leveraging the model's existing capabilities. Deleting previously tagged images would result in the loss of valuable data, training the model without reviewing tags could propagate errors, and manually labeling all images from scratch is inefficient and disregards the benefits of automation.

[Use the Azure Document Intelligence Studio - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/work-form-recognizer/9-form-recognizer-studio)


[Enrich a search index in Azure AI Search with custom classes and Azure AI Language - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/enrich-search-index-using-language-studio/03-enrich-cognitive-search-index-custom-classes)

Q:: =============================================

You are building an app that will use Azure AI Vision to analyze and classify images to build an image library of animals.
You need to configure the classification type for the Azure AI Vision project. The solution must ensure that the images selected only include a single animal.
Which type of classification should you use?

Select only one answer.

- multiclass
- multilabel
- singleclass
- singlelabel
- unilabel

A:: =============================================

1. multiclass

Multilabel classification applies any number of tags to an image (zero or more), while multiclass classification sorts images into single categories (every image you submit will be sorted into the most likely tag). Therefore, using multilabel means that one image can be tagged as both “cat” and “dog” at the same time, although it should be either/or.

[Quickstart: Build an image classification model with the Custom Vision portal - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/getting-started-build-a-classifier)

[Classify images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/classify-images/)

Q:: =============================================

You are building an app that will entify the core concepts of a document by using Azure AI Foundry Service.
Which endpoint should you use as part of the solution?

Select only one answer.

- custom Named Entity Recognition (NER)
- key phrase extraction
- the Azure AI Vision API

A:: =============================================

1. key phrase extraction

You should use the key phrase extraction endpoint.
The custom NER endpoint will not do key phrase extraction and the Azure AI Vision API can be used to process PDF files but not to extract key phrase detection.

[What is key phrase extraction in Azure Cognitive Service for Language? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/key-phrase-extraction/overview)

[Extract insights from text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

Q:: =============================================

You have an app named App1 that analyzes social media mentions and determines whether comments are positive or negative.
During testing, you notice that App1 generates negative sentiment analysis in response to customer feedback that contains positive feedback.
You need to ensure that App1 includes more granular information during the analysis.
What should you add to the API requests?

Select only one answer.

- `loggingOptOut=true`
- `StringIndexType=TextElements_v8`
- `opinionMining=true`

A:: =============================================

1. `opinionMining=true`

`opinionMining=true` will add aspect-based sentiment analysis, which in turn will make the sentiment more granular so that positive and negative in a single sentence can be returned.
`loggingOptOut=true` will opt out of logging and `StringIndexType=TextElements_v8` will set the returned offset and length values to correspond with `TextElements`.

[Text Analysis Runtime - Analyze Text - REST API (Azure Cognitive Services - Language) | Microsoft Learn](https://learn.microsoft.com/rest/api/language/text-analysis-runtime/analyze-text?view=rest-language-2023-04-01&tabs=HTTP)

[How to perform sentiment analysis and opinion mining - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/sentiment-opinion-mining/how-to/call-api)

[Extract insights from text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

Q:: =============================================

You are building a model that uses Conversational Language Understanding (CLU).
You need to train the model.
Which training methods can you use?

Select only one answer.

- advanced, deterministic, and standard
- advanced only
- deterministic only
- standard and advanced only
- standard only

A:: =============================================

1. standard and advanced only

Both standard and advanced are from CLU. Deterministic is a method from Language Understanding.

[How to train and evaluate models in Conversational Language Understanding - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/conversational-language-understanding/how-to/train-model?tabs=language-studio#training-modes)

[How to use train and test - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/luis/how-to/train-test#change-deterministic-training-settings-using-the-version-settings-api)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

Q:: =============================================

You have a question answering project.
A customer asks a question that is not part of the project.
You review the active learning suggestions and do not see any suggestions.
You need to ensure that customer questions are included in the active learning suggestions. The solution must minimize administrative effort.
What should you do?

Select only one answer.

- Add the customer questions to the editor manually.
- Configure active learning.
- Enable logging for the project.
- Wait at least 30 minutes before checking for suggestions.

A:: =============================================

1. Wait at least 30 minutes before checking for suggestions.

Active learning suggestions are not in real time. There is an approximate delay of 30 minutes before suggestions show on this pane. This delay balances the high cost involved in real-time updates to the index and service performance.
Active learning is turned on by default. You can use active learning for this instead of manually logging the questions and adding them.

[Enrich your project with active learning - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/tutorials/active-learning)

[Build a question answering solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

Q:: =============================================

You are building a GPT-based chat application that will answer questions about your company.
You plan to use the Using your data feature in Azure OpenAI to ground the model with company data.
Which four types of files can you use to ground the model? Each correct answer presents a complete solution.

Select all answers that apply.

- HTML
- MD
- PDF
- TXT
- XML
- ZIP

A:: =============================================

1. HTML
2. MD
3. PDF
4. TXT

Currently only TXT, MD, HTML, PDF, Microsoft Word, and PowerPoint files can be used and are supported using the “Using your data” feature in Azure OpenAI. ZIP and XML files are not supported.

[Using your data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/use-your-data?tabs=ai-search)

Q:: =============================================

You have an app named App1 that extracts invoice data from PDF files by using an S0 instance of Azure AI Document Intelligence. The PDF files are up to 2 MB each and contain up to 10 pages.
Users report that App1 is unable to process some invoices.
You need to troubleshoot the issue.
What is a possible cause of the issue?

Select only one answer.

- Some of the files are password protected.
- Some of the files are too large.
- Some of the files have too many pages.
- The tier of the Azure AI Document Intelligence instance is insufficient.

A:: =============================================

1. Some of the files are password protected.

The service cannot process password-protected files, and this can cause the service a processing failure for some of the files. Although file size and number of pages can cause failures, the limit for the S0 tier is 500 MB and 2,000 pages.
The S0 tier is sufficient for the file characteristics mentioned.

[Invoice data extraction – Form Recognizer - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/form-recognizer/concept-invoice?view=form-recog-3.0.0)

[Extract data from forms with Form Recognizer - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/work-form-recognizer/)

Q:: =============================================

You are building an app that will extract data from legal documents.
You plan to use the Azure AI Document Intelligence prebuilt-read model.
Which three document formats does the prebuilt-read model support? Each correct answer presents a complete solution.

Select all answers that apply.

- JSON
- Microsoft Excel
- Microsoft Word
- PDF
- TXT
- XML

A:: =============================================

1. Microsoft Excel
2. Microsoft Word
3. PDF

The prebuilt-read model supports PDF, Excel, and Word files.
TXT, JSON, and XML are unsupported by the prebuilt-read model of Azure AI Document Intelligence

[OCR for documents - Form Recognizer - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/form-recognizer/concept-read?view=form-recog-3.0.0)

[Extract data from forms with Form Recognizer - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/work-form-recognizer/)

Q:: =============================================

Your company processes scanned invoices to automate financial recordkeeping.
You need to entify and extract key fields from these invoices.
Each correct answer presents part of the solution. Which three actions should you take?

Select all answers that apply.

- Ensure input files meet required specifications.
- Select the Business Card model.
- Select the Invoice model.
- Select the Read model.
- Use low-quality images.
- Use text-based PDF files.

A:: =============================================

1. Ensure input files meet required specifications.
2. Select the Invoice model.
3. Use text-based PDF files.

Meeting input requirements, such as file format and resolution, is essential for optimal data extraction performance. Text-embedded PDFs eliminate errors in character recognition, enhancing the accuracy of data extraction and optimizing the OCR process for structured data extraction. The Microsoft Invoice model is specifically trained to extract structured data from invoices, including fields like invoice number and total amount, directly addressing the requirement for structured data extraction from invoices. Low-resolution images reduce the accuracy of data extraction, making them unsuitable for this task. The Microsoft Business Card model is tailored for extracting data from business cards, not invoices, and does not align with the goal of extracting structured data from invoices. The Microsoft Read model is designed for general text extraction and does not specialize in structured data extraction from invoices, failing to meet the specific requirements of the task.

[Understand prebuilt models - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-prebuilt-form-recognizer-models/2-understand-prebuilt-models)


[Understand AI Document Intelligence - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/plan-form-recognizer-solution/2-understand)

Q:: =============================================

Your organization is developing an AI-powered application using Azure OpenAI in Foundry Models.
You need to choose a model for text generation.
What should you recommend?

Select only one answer.

- Azure AI Vision
- Code-Davinci-003
- DALL-E
- GPT-4

A:: =============================================

1. GPT-4

Azure AI Vision is designed for analyzing visual content and does not support text generation, making it unsuitable for the scenario. Code-Davinci-003 is optimized for code generation tasks and lacks the capabilities required for text generation, which disqualifies it as a viable option. DALL-E specializes in generating images from textual descriptions and does not meet the requirement for text generation. GPT-4, on the other hand, is specifically designed for generating detailed and contextually accurate text responses, making it the most appropriate choice for the given requirement.

[Azure AI services - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-services)


[Plan and prepare to develop AI solutions on Azure - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-openai/2-access-azure-openai)

Q:: =============================================

You are building an app that will use an Azure AI Foundry Service resource.
You need to entify the endpoint for the resource.
From the Azure CLI, which command should you run?

Select only one answer.

- `az cognitiveservices account show `
- `az cognitiveservices account show --name myresource`
- `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group `
- `az cognitiveservices account show --resource-group cognitive-services-resource-group `

A:: =============================================

1. `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group `

As you need to prove the name and the resource group for your Cognitive Service account to retrieve the endpoint amongst other information for the resource, `az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group` is the only valcommand.

[az cognitiveservices account | Microsoft Learn](https://learn.microsoft.com/cli/azure/cognitiveservices/account?view=azure-cli-latest#az-cognitiveservices-account-show)

[Create and consume Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-manage-cognitive-services/)

Q:: =============================================

You are building an app that will use Azure AI Custom Vision. The app will be deployed to a virtual machine in Azure.
You enable firewall rules for your Azure AI Services account.
You need to ensure that the app can access the service through a service endpoint.
What should you do?

Select only one answer.

- Assign a role-based access control (RBAC) role to the Azure AI Custom Vision resource.
- Grant access to a specific virtual network.
- Grant access to an internet IP range.
- Include an access token in the Authorization header.

A:: =============================================

1. Grant access to a specific virtual network.

If you enable the firewall for the Azure AI Services account, you need to allow network access to the service. You can achieve this by either allowing access from a specific virtual network or adding an IP range to the firewall rules. In this situation, the app is deployed to a virtual machine in Azure, which reses in a virtual network. You can prove access to virtual networks in Azure to access specific service endpoints.

[Configure Virtual Networks for Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/cognitive-services-virtual-networks?context=%2Fazure%2Fcognitive-services%2Fcustom-vision-service%2Fcontext%2Fcontext&tabs=portal)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

Q:: =============================================

You have an Azure App Services web app named App1.
You need to configure App1 to use Azure AI Services to authenticate by using Microsoft Entra . The solution must meet the following requirements:

- Minimize administrative effort.

- Use the principle of least privilege.

What should you do?

Select only one answer.

- Create a secret and store the secret in an Azure key vault. Assign App1 role-based access control (RBAC) permissions to the secret.
- Create a Microsoft Entra app registration and enable certificate-based authentication.
- From App1, enable a managed entity and assign role-based access control (RBAC) permissions to Azure AI Services.
- From PowerShell, create a secret that never expires.

A:: =============================================

1. From App1, enable a managed entity and assign role-based access control (RBAC) permissions to Azure AI Services.

With a managed entity, the rotation of the secrets (certificates) is done automatically.
You still need to rotate secrets by using the key vault, and you cannot create secrets that never expire from the portal. It is not consered best practice to create one with PS1 or the CLI, and a certificate will also expire at some point.

[Authentication in Azure Cognitive Services - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/authentication?tabs=powershell#authorize-access-to-managed-entities)

[Secure Cognitive Services - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/secure-cognitive-services/)

Q:: =============================================

You create an Azure AI Foundry Content Safety solution to monitor the text input of a chat forum.
You discover that the solution returns a severity level of 0 for various instances of harmful text.
Which type of accuracy error is returned by the solution?

Select only one answer.

- a false negative
- a false positive
- a true negative
- a true positive

A:: =============================================

1. a false negative

A false negative arises when the model fails to entify harmful content and returns a severity level of 0. There are four accuracy error types, and a false negative indicates incorrectly accepted content in the text.

[Transparency Note and use cases for AI Content Safety - Azure AI services | Microsoft Learn](https://learn.microsoft.com/legal/cognitive-services/content-safety/transparency-note?context=%2Fazure%2Fai-services%2Fcontent-safety%2Fcontext%2Fcontext)

Q:: =============================================

You are building an image moderation solution based on Azure AI Foundry Content Safety.
You migrate images to an Azure Blob Storage location.
You need to configure an access solution to enable the Foundry Content Safety solution to analyze the images.
Which two actions should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

- Assign the Storage Blob Data Contributor/Owner/Reader role to the user-assigned managed entity.
- Assign the Storage Blob Data Contributor/Owner/Reader role to the system-assigned managed entity.
- Enable a system-assigned managed entity for the Content Safety instance.
- Enable a user-assigned managed entity for the Content Safety instance.

A:: =============================================

1. Assign the Storage Blob Data Contributor/Owner/Reader role to the system-assigned managed entity.
2. Enable a system-assigned managed entity for the Content Safety instance.

The only way to prove a Content Safety resource with access to images in Azure Blog Storage, is to enable a system-assigned managed entity and to assign the role Storage Blob Data Contributor/Owner/Reader to that managed entity. User-assigned managed entities are not permitted in that scenario.

[Quickstart: Analyze image content - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-image?tabs=visual-studio%2Cwindows&pivots=programming-language-rest)

Q:: =============================================

You are building an app that will use the Azure AI Custom Vision API to detect when all the spaces in a parking lot are empty.
Which feature of the API should you use?

Select only one answer.

- image classification
- image description
- object detection

A:: =============================================

1. object detection

Object detection is similar to image classification, but it returns the coordinates in an image where the applied label(s) can be found.
Image description analyzes an image and generates a human-readable phrase that describes its contents. Image classification applies one or more labels to an entire image.

[What is Custom Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/overview)

[Detect objects in images - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-objects-images/)

Q:: =============================================

You are using a custom Language content model in an Azure AI Veo Indexer solution.
During testing, you upload a text file that includes the following sentence: “Kubernetes is a new feature in Azure & the cloud.”
The sentence is discarded.
You need to ensure that the model retains the sentence.
What should you do?

Select only one answer.

- Change the model to a custom slate detection model.
- Remove the “&” character from the text file.
- Retrain the model.

A:: =============================================

1. Remove the “&” character from the text file.

You need to remove the “&” character because sentences with special characters will be discarded.
Kubernetes is highly specific and unknown to the model, so retraining the model is incorrect. The slate model is for clapper boards and digital patterns with color bars.

[Customize a Language model in Azure Veo Indexer - Azure - Azure Veo Indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-veo-indexer/customize-language-model-overview)

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-veo/)

Q:: =============================================

You are deploying an Azure OpenAI in Foundry Models service.
You plan to use your own data in the models you will deploy.
You need to ensure that the model can index your data sources.
Which additional Azure service should you deploy?

Select only one answer.

- Azure AI Search
- Content Moderator
- Language
- Personalizer

A:: =============================================

1. Azure AI Search

Azure OpenAI on your data enables developers to use supported AI chat models that can reference specific sources of information to ground the response. Adding this information allows the model to reference both the specific data proved and its pretrained knowledge to prove more effective responses. Azure OpenAI on your data utilizes the search ability of Azure AI Search to add the relevant data chunks to a prompt.
Azure OpenAI on your data still uses a stateless API to connect to the model, which removes the requirement of training a custom model with your data and simplifies the interaction with the AI model. Cognitive Search first finds the useful information to answer the prompt, and Azure OpenAI forms the response based on that information.

[Develop a RAG-based solution with your own data using Azure AI Foundry - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/)

[What are Azure AI services? - Azure AI services | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/what-are-ai-services)

Q:: =============================================

You are building a knowledge mining solution by using Azure AI Search.
You need to ensure that the solution supports wildcard queries in search requests.
What should you include in the REST API request?

Select only one answer.

- `“queryType”: “extended” `
- `“queryType”: “full” `
- `“queryType”: “simple”`
- `“queryType”: “wildcard”`

A:: =============================================

1. `“queryType”: “full” `

queryType “full” extends the default Simple query language by adding support for more operators and query types, such as wildcard, fuzzy, regex, and field-scoped queries.

[Full text query and indexing engine architecture (Lucene) - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/search-lucene-query-architecture)

[Create an Azure Cognitive Search solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are building an app that will recognize the intent and entities of user utterances in real-time.
You are evaluating the use of intent recognition with the Azure AI Speech and Azure AI Language services or simple pattern matching.
When should you use pattern matching?

Select only one answer.

- You are only interested in matching strictly what the user sa.
- You must manage the model by using a web app.
- You must use a machine learned entity.
- You must use a prebuilt entity.

A:: =============================================

1. You are only interested in matching strictly what the user sa.

The only option is to use pattern matching over Language Understanding when you want to strictly match what a user sa, as the incorrect options are only available in Language Understanding.

[How to recognize intents with custom entity pattern matching - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/how-to-use-custom-entity-pattern-matching?tabs=jre%2Cwindows%2Cubuntu%2Cmaven&pivots=programming-language-csharp)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

Q:: =============================================

You are building a multilingual conversational app by using Conversational Language Understanding (CLU), part of Azure AI Language service.
You create a CLU model that will serve multiple languages.
You need to optimize the performance of the model. The solution must minimize development effort.
What should you do?

Select only one answer.

- Add utterances for languages that are performing poorly in the model.
- Configure the app to only query utterances in the language that was used to train the model.
- Create separate projects for each language.
- Train the model by using utterances in multiple languages and only query the model by using the project language.

A:: =============================================

1. Add utterances for languages that are performing poorly in the model.

With CLU, there is no need to use multiple projects for a model. For example, you can train a model in English and query it in German. There is no project language, therefore, adding utterances for languages in the model that are performing poorly is the appropriate solution to increase performance.

[Multilingual projects - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/conversational-language-understanding/concepts/multiple-languages)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

Q:: =============================================

You are building an app that uses Azure AI Services Document Translation.
You need to improve the quality of the translation for user-uploaded documents.
What should you ask the users to include when they upload a document?

Select only one answer.

- a summary
- the file format
- the source language
- the writing style

A:: =============================================

1. the source language

If the language of the content in the source document is known, it is recommended to specify the source language in the request to get a better translation.

[Frequently asked questions - Document Translation - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/document-translation/faq)

[Translate text with the Translator service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translator-service/)

Q:: =============================================

Your company needs to analyze images of retail shelves to entify product placement and stock levels.
You need to implement a Microsoft Azure AI solution to analyze these images.
What should you use?

Select only one answer.

- Train an Azure AI Custom Vision model.
- Use Azure AI Content Understanding.
- Use an Azure AI Vision prebuilt model.
- Use an Azure AI Foundry GPT model.

A:: =============================================

1. Use Azure AI Content Understanding.

Azure AI Content Understanding is the most appropriate solution as it is specifically designed to analyze images and extract structured data, such as product counts, directly addressing the requirements. Training a Custom Vision model would require additional effort and resources without proving any significant advantage over the existing capabilities of Azure AI Content Understanding. Prebuilt Azure AI Vision models can detect bounding boxes but does not offer the ability to count or extract structured data about products, making it unsuitable for this task. Azure AI Foundry GPT models can prove information based on proved data or information but is unable to achieve the desired result on its own.

[Azure AI Content Understanding image solutions (preview) - Training | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/image/overview)

Q:: =============================================

You build an app named App1 that uses the Azure AI Face service.
You need to optimize the app for images that contain blurry faces.
What should you do?

Select only one answer.

- Change the recognition model to `recognition_02`.
- Decrease the `faceTimeToLive` value.
- Set the detection model to `detection_03`.

A:: =============================================

1. Set the detection model to `detection_03`.

Model_3 Improves accuracy on small, se-view, and blurry faces.
Changing the recognition model to recognition_02 will improve facial recognition and faceTimeToLive is used for the number of seconds that the face is cached, which has no impact on blurry faces.

[How to specify a detection model - Face - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/how-to/specify-detection-model)

[Detect, analyze, and recognize faces - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-analyze-recognize-faces/)

Q:: =============================================

You need to build an app that will summarize text documents into key phrases.
Which Azure AI Language feature should you recommend?

Select only one answer.

- Language Summarization
- key phrase extraction
- Named Entity Recognition (NER)
- Personally entifiable Information (PII) detection

A:: =============================================

1. key phrase extraction

Key phrase extraction is used to quickly entify the main concepts in text, whereas the other features do not return key phrases from longer text documents.

[What is key phrase extraction in Azure Cognitive Service for Language? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/key-phrase-extraction/overview)

[Extract insights from text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

Q:: =============================================

You are building a web app that will generate images based on user prompts. The app will use the DALL-E 3 Azure OpenAI model.
You need to ensure that HTTP requests against the Azure OpenAI API successfully generate images.
Which HTTP body property should you include?

Select only one answer.

- the API version
- the Azure OpenAI resource name
- the deployment - the prompt

A:: =============================================

1. the prompt

The prompt is the only required property to be used in the body of the HTTP request when requesting to generate a new image by using the DALL-E 3 Azure OpenAI API. The other properties are used in the HTTP header.

[Azure OpenAI Service REST API reference - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/reference#image-generation)

Q:: =============================================

You are building an app that will use Azure AI Vision to detect the presence of people in a veo feed.
Which Azure AI Vision feature should you use?

Select only one answer.

- face detection
- Image Analysis
- optical character recognition (OCR)
- Spatial Analysis

A:: =============================================

1. Spatial Analysis

The only visual feature that proves this capability is Spatial Analysis, as OCR, Image Analysis, and face detection are not meant to analyze the presence of people in a veo feed.

[What is Computer Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview)

[Analyze veo - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-veo/)

Q:: =============================================

You are configuring a question answering solution.
You execute the following API call and receive the following error.
```
"synonyms": [
        {
            "alterations": [
                "fix problems",
                "troubleshoot",
                "#diagnostic",
                ]
        },
...
```
You need to ensure that the API call executes successfully.
What should you do?

Select only one answer.

- Modify the order of the synonyms.
- Remove any question and answer pairs from the call.
- Remove any special characters from the call.

A:: =============================================

1. Remove any special characters from the call.

Special characters are not allowed for synonyms.
Synonyms can be added in any order, and the ordering is not consered in any computational logic. Synonyms can only be added to a project that has at least one question and answer pair.

[Improve the quality of responses with synonyms - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/question-answering/tutorials/adding-synonyms)

[Build a question answering solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-qna-solution-qna-maker/)

Q:: =============================================

You are building a solution that uses Azure AI Search.
You need to define the field attributes for a field where the search results will include a hit count by category.
Which attribute should you assign to the field?

Select only one answer.

- `facetable`
- `filterable `
- `key`

A:: =============================================

1. `facetable`

`facetable` is typically used in a presentation of search results that includes a hit count by category.
`Filterable` is referenced in `$filter` queries, and `key` is a unique entifier for documents within the index.

[Index overview - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/search-what-is-an-index)

[Create an Azure Cognitive Search solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are building a solution that uses Azure AI Search.
You need to execute the initial run of the indexer.
Which stages will be included during the initial run?

Select only one answer.

- connecting to an Azure data source, creating an index schema, and running the wizard to create objects and load data
- creating a data source, creating an index, and creating and running the indexer
- document cracking, field mapping, skillset execution, and output field mapping

A:: =============================================

1. document cracking, field mapping, skillset execution, and output field mapping

Document cracking, field mapping, skillset execution, and output field mapping are the stages of indexing.
Creating a data source, creating an index, and creating and running the indexer are the stages to create an indexer. Connecting to an Azure data source, creating an index schema, and running the wizard to create objects and load data are the stages for the Import Data wizard.

[Indexer overview - Azure Cognitive Search | Microsoft Learn](https://learn.microsoft.com/azure/search/search-indexer-overview#stages-of-indexing)

[Create an Azure Cognitive Search solution - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/create-azure-cognitive-search-solution/)

Q:: =============================================

You are creating an orchestration workflow for Language Understanding.
You need to configure workflows for multiple languages. The solution must minimize administrative effort.
What should you create for each language?

Select only one answer.

- a new deployment
- separate models
- separate training jobs
- separate workflow projects

A:: =============================================

1. separate workflow projects

Orchestration workflow projects do not support the multilingual option, so you need to create a separate workflow project for each language.

[Language support for orchestration workflow - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/orchestration-workflow/language-support)

[Build a Language Understanding model - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/build-language-understanding-model/)

Q:: =============================================

You have an app that sends audio recordings from a call center to the speech-to-text feature of Azure AI Foundry Service.
During testing, you notice that the Word Error Rate (WER) is high and there are a lot of substitution errors.
You need to improve the model and reduce the WER.
What should you add to the training data?

Select only one answer.

- custom product and people names
- overlapping speakers
- people talking in the background

A:: =============================================

1. custom product and people names

Substitution errors are due to the model needing more training on custom product names and people names.
Overlapping speakers define when there are more deletion errors. People talking in the background are detected when there are more insertion errors.

[Test accuracy of a Custom Speech model - Speech service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/how-to-custom-speech-evaluate-data?pivots=speech-studio#resolve-errors-and-improve-wer)

[Create speech-enabled apps with the Speech service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/transcribe-speech-input-text/)

---

DECK INFO

TARGET DECK: Programming::Cloud::Azure::MAAEA - Azure ai engineer associate - microsoft learn

FILE TAGS: #Programming::#Cloud::#Azure::#AI-102

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```
