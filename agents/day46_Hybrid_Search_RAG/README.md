# 👀 RAG App with Hybrid Search 🔍

## 💡 Problem

Traditional document Q&A apps often fail to combine semantic understanding of uploaded documents with general knowledge reasoning. Users need a system that can provide accurate, context-aware answers across both domain-specific and general queries.

## 🚀 Solution

The **Hybrid Search RAG App** uses a multi-model approach combining RAGLite for document retrieval, Claude for text generation, OpenAI for embeddings, and Cohere for reranking. It integrates hybrid search (semantic + keyword matching) to provide accurate, contextual answers while seamlessly handling general knowledge queries.

## ⚙️ Features

* **Hybrid Search Question Answering**:

  * RAG-based answers for document-specific queries
  * Fallback to Claude for general knowledge questions

* **Document Processing**:

  * PDF upload and processing
  * Automatic text chunking and embedding
  * Hybrid search combining semantic and keyword matching
  * Reranking for better context selection

* **Multi-Model Integration**:

  * Claude (Claude 3 Opus) for text generation
  * OpenAI (text-embedding-3-large) for embeddings
  * Cohere (3.5 reranker) for document reranking

## 🧠 Tech Stack

* RAGLite (Document retrieval)
* Claude (Text generation)
* OpenAI (Embeddings)
* Cohere (Reranking)
* PostgreSQL / MySQL / SQLite (Database)
* Streamlit (Interface)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* PostgreSQL (Neon recommended), MySQL, or SQLite
* OpenAI API Key
* Anthropic API Key (Claude)
* Cohere API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day46_Hybrid_Search_RAG
pip install -r requirements.txt
pip install https://github.com/explosion/spacy-models/releases/download/xx_sent_ud_sm-3.7.0/xx_sent_ud_sm-3.7.0-py3-none-any.whl
```

### Running the App

```bash
streamlit run main.py
```

### Configuration

* Enter API keys in the sidebar:

  * OpenAI
  * Anthropic (Claude)
  * Cohere
  * Database URL (optional, defaults to SQLite)
* Click "Save Configuration"

## 🧭 Real-World Use Cases

* Enterprise knowledge Q&A with both domain-specific and general queries
* Academic research assistants for PDF and text-based sources
* Legal or compliance document search with intelligent retrieval
* Educational chat systems combining hybrid search and AI reasoning

## 📁 Repository Info

* **Project Name**: RAG App with Hybrid Search
* **Day Number**: 46
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: RAGLite, Claude, OpenAI, Cohere, PostgreSQL/MySQL/SQLite, Streamlit
* **License**: MIT
