<a name="readme-top"></a>

<p align="center">
    <b>Symbiot: Your Best Organizational <i>assistant!</i></b>. <br />
    An efficient, customizable, and enterprise-ready document assistant solution.
</p>

A full-stack application that enables you to turn any document, resource, or piece of content into context that any LLM can use as references during chatting. This application allows you to pick and choose which LLM or Database you want to use as well as supporting multi-user management and permissions.

### Product Overview

Symbiot is a full-stack application where you can use commercial off-the-shelf LLMs or popular open source LLMs and vectorDB solutions to build a private ChatGPT with no compromises that you can run locally as well as host remotely and be able to chat intelligently with any documents you provide it.

Symbiot divides your documents into objects called `workspaces`. A Workspace functions a lot like a thread, but with the addition of containerization of your documents. Workspaces can share documents, but they do not talk to each other so you can keep your context for each workspace clean.

Some cool features of Symbiot

- **Multi-user instance support and permissioning**
- **_New_** [Custom Embeddable Chat widget for your website](./embed/README.md)
- Multiple document type support (PDF, TXT, DOCX, etc)
- Manage documents in your Database from a simple UI
- Two chat modes `conversation` and `query`. Conversation retains previous questions and amendments. Query is simple QA against your documents
- In-chat citations
- 100% Cloud deployment ready.
- "Bring your own LLM" model.
- Extremely efficient cost-saving measures for managing very large documents. You'll never pay to embed a massive document or transcript more than once. 90% more cost effective than other document chatbot solutions.
- Full Developer API for custom integrations!

### Supported LLMs, Embedders, and Databases

**Supported LLMs:**

- [Any open-source llama.cpp compatible model](/server/storage/models/README.md#text-generation-llm-selection)
- [OpenAI](https://openai.com)
- [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
- [Anthropic ClaudeV2](https://www.anthropic.com/)
- [Google Gemini Pro](https://ai.google.dev/)
- [Ollama (chat models)](https://ollama.ai/)
- [LM Studio (all models)](https://lmstudio.ai)
- [LocalAi (all models)](https://localai.io/)
- [Together AI (chat models)](https://www.together.ai/)
- [Mistral](https://mistral.ai/)

**Supported Embedding models:**

- [Symbiot Native Embedder](/server/storage/models/README.md) (default)
- [OpenAI](https://openai.com)
- [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
- [LM Studio (all)](https://lmstudio.ai)
- [LocalAi (all)](https://localai.io/)

**Supported Databases:**

- [LanceDB](https://github.com/lancedb/lancedb) (default)
- [Astra DB](https://www.datastax.com/products/datastax-astra)
- [Pinecone](https://pinecone.io)
- [Chroma](https://trychroma.com)
- [Weaviate](https://weaviate.io)
- [QDrant](https://qdrant.tech)
- [Milvus](https://milvus.io)
- [Zilliz](https://zilliz.com)
