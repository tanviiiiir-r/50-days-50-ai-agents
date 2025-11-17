# 🐋 Deepseek Local RAG Reasoning Agent 🤖

## 💡 Problem

Most AI chat agents lack integrated reasoning with local models and external document knowledge. Users need a system that combines local model speed with RAG-enhanced reasoning and document grounding for accurate and context-aware responses.

## 🚀 Solution

The **Deepseek Local RAG Reasoning Agent** combines local Deepseek models with RAG capabilities using Qdrant, Snowflake embeddings, and Agno orchestration. Users can interact locally, upload documents, perform advanced reasoning, and query both local and web sources, with real-time visualization of the agent's thought process.

## ⚙️ Features

* **Dual Operation Modes**:

  * Local Chat Mode: Direct local interaction with Deepseek.
  * RAG Mode: Reasoning enhanced by documents and web search (via llama3.2).

* **Document Processing (RAG Mode)**:

  * PDF upload and content extraction.
  * Web page scraping and text chunking.
  * Vector embeddings stored in Qdrant.

* **Intelligent Querying (RAG Mode)**:

  * RAG-based retrieval and similarity search.
  * Fallback to web search when local data insufficient.
  * Source attribution included.

* **Advanced Capabilities**:

  * Exa AI web search integration.
  * Domain-specific filtering.
  * Context-aware responses.
  * Chat history management and thinking visualization.

* **Model Specific Features**:

  * Deepseek r1 1.5b (lightweight) or 7b (advanced)
  * Snowflake Arctic Embedding model
  * Agno framework for orchestration
  * Streamlit UI

## 🧠 Tech Stack

* Deepseek (Local LLM)
* Llama 3.2 (RAG reasoning)
* Snowflake Arctic Embeddings
* Qdrant Cloud (Vector database)
* Agno Agent framework
* Exa AI (Web search)
* Streamlit (Interface)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Ollama installed with Deepseek models
* Qdrant Cloud credentials
* Exa AI API key (optional)

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day44_Deepseek_Local_RAG_Agent
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run deepseek_rag_agent.py
```

### Model Setup

```bash
# Ollama model pulls
ollama pull deepseek-r1:1.5b
ollama pull deepseek-r1:7b
ollama pull snowflake-arctic-embed
ollama pull llama3.2
```

### Qdrant Cloud Setup

* Sign up at [Qdrant Cloud](https://cloud.qdrant.io/)
* Create cluster and obtain API Key and URL

### Optional Exa AI API Key

* Sign up at [Exa AI](https://exa.ai)
* Generate API key for web search integration

## 🧭 Real-World Use Cases

* Local AI assistants with reasoning and document grounding.
* Research and corporate knowledge retrieval from PDFs and web sources.
* Advanced educational tools providing context-aware responses.
* Real-time thinking visualization for AI transparency.

## 📁 Repository Info

* **Project Name**: Deepseek Local RAG Reasoning Agent
* **Day Number**: 44
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Deepseek, Llama 3.2, Snowflake Arctic Embeddings, Qdrant, Agno, Exa AI, Streamlit
* **License**: MIT
