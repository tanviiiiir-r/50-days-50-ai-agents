# 🔄 Corrective RAG Agent 🤖

## 💡 Problem

Standard RAG systems may provide incomplete or irrelevant answers when document retrieval or query formulation fails. Users require a system that can self-correct, optimize queries, and combine both local and web sources for accurate responses.

## 🚀 Solution

The **Corrective RAG Agent** uses a multi-stage workflow powered by LangGraph. It combines smart document retrieval, relevance grading, query optimization, and web search fallback to deliver contextually accurate answers. Users can upload documents, ask questions, and observe the corrective reasoning process in real-time.

## ⚙️ Features

* **Smart Document Retrieval**: Qdrant vector store enables efficient document lookup.
* **Document Relevance Grading**: Claude 4.5 sonnet evaluates document relevance.
* **Query Transformation**: Optimizes queries for better search results.
* **Web Search Fallback**: Tavily API provides additional sources when local documents are insufficient.
* **Multi-Model Approach**: OpenAI embeddings combined with Claude 4.5 sonnet for different tasks.
* **Interactive UI**: Streamlit interface for document upload, querying, and real-time visualization.

## 🧠 Tech Stack

* LangChain (RAG orchestration)
* LangGraph (Workflow management)
* Qdrant (Vector database)
* Claude 4.5 sonnet (Language model)
* OpenAI (Embeddings)
* Tavily (Web search)
* Streamlit (User interface)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* OpenAI API key
* Anthropic API key (Claude 4.5 sonnet)
* Tavily API key
* Qdrant Cloud account and credentials

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day43_Corrective_RAG
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run corrective_rag.py
```

### API Keys Configuration

1. OpenAI API key for embeddings.
2. Anthropic API key for Claude 4.5 sonnet.
3. Tavily API key for web search.
4. Qdrant API key and cluster URL.

### Usage

* Upload documents or input URLs.
* Enter queries in the input field.
* Observe step-by-step corrective RAG reasoning.
* Receive comprehensive answers.

## 🧭 Real-World Use Cases

* Enterprise knowledge retrieval with accurate document grounding.
* Legal or compliance document analysis.
* Research assistants with dynamic fallback to web sources.
* Educational tools providing verified, context-aware answers.

## 📁 Repository Info

* **Project Name**: Corrective RAG Agent
* **Day Number**: 43
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: LangChain, LangGraph, Qdrant, Claude 4.5 sonnet, OpenAI, Tavily, Streamlit
* **License**: MIT
