# AI Toolkit
**Tools, frameworks, and other resources for building AI applications.**

---------------------------------------------------------

## Tools from Industry Leaders
* AWS
    + **[Amazon Bedrock](https://aws.amazon.com/bedrock/)**: Build and scale generative AI applications with foundation models.
    + **[Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/)**: AI-powered productivity tool for the IDE and command line.
    + **[Amazon SageMaker](https://aws.amazon.com/sagemaker/)**: Build, train, and deploy machine learning models for any use case with fully managed infrastructure, tools, and workflows.
    + **[AWS AI Services](https://aws.amazon.com/machine-learning/ai-services/)**: Pre-trained AI Services to easily integrate with your applications to address common use cases such as personalized recommendations, modernizing your contact center, improving safety and security, and increasing custom engagement.
        + **[Amazon Comprehend](https://aws.amazon.com/comprehend/?c=ml&sec=srv)**: Process text to extract key phrases, entities, and sentiment for further analysis.        
        + **[Amazon Forecast](https://aws.amazon.com/forecast/?c=ml&sec=srv)**: Forecast business outcomes easily and accurately using machine learning.
        + **[Amazon Kendra](https://aws.amazon.com/kendra/?c=ml&sec=srv)**: Find accurate information faster.
        + **[Amazon Lex](https://aws.amazon.com/lex/?c=ml&sec=srv)**: Build and deploy conversational AI interfaces.
        + **[Amazon Rekognition](https://aws.amazon.com/rekognition/?c=ml&sec=srv)**: Automate and lower the cost of your image recognition and video analysis with machine learning.
        + **[Amazon Textract](https://aws.amazon.com/textract/?c=ml&sec=srv)**: Automatically extract printed text, handwriting, layout elements, and data from any document.

* Google
    + **[Gemini API (documentation)](https://ai.google.dev/docs/gemini_api_overview)**: Access to the latest generative models from Google.
    + **[Google AI Studio (documentation)](https://ai.google.dev/tutorials/ai-studio_quickstart)**: A browser-based IDE for prototyping with generative models.

* Microsoft
    + **[Azure AI Services (documentation)](https://learn.microsoft.com/en-us/azure/ai-services/)**: Pre-built and customizable APIs and models for applications with natural language processing capabilities including conversations, search, monitoring, translation, speech, vision, and decision-making.
      +   **[Azure AI Search](https://learn.microsoft.com/en-us/azure/search/)** (formerly Azure Cognitive Search): Information retrieval at scale for vector and text content in traditional or generative search scenarios.
      +   [Bot Service](https://learn.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0): An integrated environment that is purpose-built for bot development.
      +   [Custom Vision](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/): Build, deploy, and improve your own image classifiers.
      +   [Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/?view=doc-intel-4.0.0) (formerly Form Recognizer): Uses machine learning models to automate your data processing in applications and workflows.
      +   [Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/): Extract information, classify text, understand conversational language, answer questions, and more.
      +   **[Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)**: Access to OpenAI's models including GPT-4, GPT-4 Turbo with Vision, GPT-3.5-Turbo, DALLE-3 and Embeddings model series with the security and enterprise capabilities of Azure.
      +   [Speech](https://learn.microsoft.com/en-us/azure/ai-services/language-service/): Recognize speech, synthesize speech, get real-time translations, transcribe conversations, or integrate speech into your bot experiences.
      +   [Translator](https://learn.microsoft.com/en-us/azure/ai-services/translator/): Translate text and documents with a simple REST API call.
      +   [Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/): Access to advanced algorithms for processing images and returning information.
    + **[Azure Machine Learning (documentation)](https://learn.microsoft.com/en-us/azure/machine-learning/?view=azureml-api-2)**: Train and deploy models and manage the ML lifecycle (MLOps).
    + **[Microsoft Copilot for Microsoft 365 (documentation)](https://learn.microsoft.com/en-us/microsoft-365-copilot/)**: AI-powered productivity tool that coordinates large language models (LLMs), content in Microsoft Graph, and the Microsoft 365 apps.
    + **[Teams AI Library (documentation)](https://learn.microsoft.com/en-us/microsoftteams/platform/bots/how-to/teams%20conversational%20ai/teams-conversation-ai-overview)**: Provides a simple capabilities-driven approach and helps you to create intelligent apps quickly and easily with prebuilt, reusable code snippets so that you can focus on building the business logic rather than learning the semantics of Teams conversational applications.

* Robotic Process Automation (RPA)
    + **[Automation Anywhere](https://www.automationanywhere.com/products/automation-ai)**: Create a system of work with a connected suite of intelligent automation apps and tools to discover, automate, scale, and engage.
    + **[Microsoft — AI Builder](https://www.uipath.com/automation/ai-and-rpa)**: Automate processes and gain insights from your data using a pre-built or custom AI model for your needs in Power Apps and Power Automate.
    + **[UiPath](https://www.uipath.com/automation/ai-and-rpa)**: Rapidly build AI-powered automation that seamlessly collaborates with people and systems to transform every facet of work.

* Vector Databases
    + **[Chroma (open-source, documentation)](https://docs.trychroma.com/)**: Embedding database making it easy to build LLM apps by making knowledge, facts, and skills pluggable for LLMs.
    + **[Pinecone (documentation)](https://docs.pinecone.io/docs/overview)**: A managed, cloud-native vector database with a simple API and no infrastructure hassels.
    + **[Qdrant (documentation)](https://qdrant.tech/documentation/)**: A vector similarity search engine with a convenient API to store, search, and manage vectors with an additional payload.
    + **[Weaviate (open-source, documentation)](https://weaviate.io/developers/weaviate)**: Store and retrieve data objects and vector embeddings, seamlessly connect to your favorite ML models, and build intuitive and reliable AI applications that scale.


## Frameworks
+ **[AI.JSX (open-source)](https://www.fixie.ai/docs)**: Build AI-powered applications in JavaScript and JSX that can be deployed anywhere Node.js is supported.
+ **[LangChain (open-source)](https://python.langchain.com/docs/get_started/introduction)**: Develop applications powered by language models.
    +   LangChain libraries: [Python](https://python.langchain.com/docs/get_started/installation) and [JavaScript](https://js.langchain.com/docs/get_started/introduction)
    +   LangChain [templates](https://python.langchain.com/docs/templates): popular templates include Retrieval Augmented Generation Chatbot, Extraction with OpenAI Functions, Local Retrieval Augmented Generation, OpenAI Functions Agent, and XML Agent.
    +   [LangServe](https://github.com/langchain-ai/langserve): Helps developers deploy LangCahin runnables and chains as a REST API.
    +   [LangSmith (currently in private beta)](https://docs.smith.langchain.com/): Debug, test, evaluate, and monitor chains and intelligent agents.
+ **[LlamaIndex (open-source)](https://www.llamaindex.ai/)**: A simple, flexible data framework for connecting custom data sources to large language models.


## Other Resources
+ **[Prompt Engineering Guide](https://www.promptingguide.ai/)**: An introduction to prompt engineering and various techniques for prompting.
