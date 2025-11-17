# 🤔 Agentic RAG with Gemini Flash Thinking ⚡

## 💡 Problem

Standard RAG agents often struggle with query optimization and seamless integration of local documents and web sources. Users need a system that can intelligently rewrite queries, retrieve relevant documents, and fallback to web search for comprehensive, context-aware responses.

## 🚀 Solution

The **Agentic RAG with Gemini Flash Thinking** leverages Gemini 2.0 Flash Thinking and gemini-exp-1206 models for reasoning and embeddings. With Qdrant for vector storage and Agno for agent orchestration, this system offers document processing, query rewriting, and advanced retrieval to deliver accurate, grounded AI responses.

## ⚙️ Features

* **Document Processing**:

  * PDF upload and processing
  * Web page content extraction
  * Automatic text chunking and embedding
  * Vector storage in Qdrant

* **Intelligent Querying**:

  * Query rewriting for improved retrieval
  * RAG-based document retrieval
  * Similarity search with threshold filtering
  * Automatic fallback to web search
  * Source attribution for answers

* **Advanced Capabilities**:

  * Exa AI web search integration
  * Domain-specific filtering for web search
  * Context-aware response generation
  * Chat history management
  * Query reformulation agent

* **Model Specific Features**:

  * Gemini Thinking 2.0 Flash for chat and reasoning
  * Gemini Embedding model for vector embeddings
  * Agno Agent framework for orchestration
  * Streamlit-based interactive interface

## 🧠 Tech Stack

* Gemini 2.0 Flash Thinking (Reasoning)
* Gemini Embedding model
* Agno (Agent orchestration)
* Qdrant (Vector storage)
* Exa AI (Optional web search)
* Streamlit (Interface)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Google API Key
* Qdrant Cloud account
* Optional Exa AI API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day45_Gemini_Agentic_RAG
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run agentic_rag_gemini.py
```

### API Keys Configuration

1. Google API Key for AI Studio access
2. Qdrant API Key and Cluster URL
3. Optional Exa AI API Key for web search

## 🧭 Real-World Use Cases

* Research assistants that integrate PDFs and web sources for comprehensive answers
* Enterprise knowledge retrieval with query optimization
* Educational tools providing context-aware and transparent reasoning
* AI chat systems with real-time query rewriting and source attribution

## 📁 Repository Info

* **Project Name**: Agentic RAG with Gemini Flash Thinking
* **Day Number**: 45
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Gemini 2.0 Flash Thinking, Gemini Embedding, Agno, Qdrant, Exa AI, Streamlit
* **License**: MIT
