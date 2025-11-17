# 🔥 Agentic RAG with EmbeddingGemma 🧠

## 💡 Problem

Accessing and leveraging knowledge from multiple PDFs for AI-powered responses can be slow and inefficient. Existing solutions often rely on cloud-based embeddings and LLMs, which can be costly, slow, or privacy-sensitive.

## 🚀 Solution

This project provides a **fully local agentic Retrieval-Augmented Generation (RAG) system** using Google's EmbeddingGemma for vector embeddings and Llama 3.2 for text generation. Users can dynamically add PDF sources, perform semantic searches, and get AI-generated responses in real-time, all via a sleek Streamlit interface.

## ⚙️ Features

* **Local AI Models**: EmbeddingGemma for embeddings and Llama 3.2 for text generation, all running locally.
* **PDF Knowledge Base**: Add PDF URLs to build a custom, searchable knowledge base.
* **Vector Search**: Efficient similarity search powered by LanceDB.
* **Interactive UI**: Streamlit interface for adding sources, querying, and viewing real-time responses.
* **Streaming Responses**: Observe AI responses as they are generated, including tool call visibility.

## 🧠 Tech Stack

* Agno (AI agent framework)
* Streamlit (Web app interface)
* LanceDB (Vector database)
* Ollama (Local LLM server)
* EmbeddingGemma (Google embedding model)
* Llama 3.2 (Meta LLM)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Ollama installed and running
* Models: `embeddinggemma:latest`, `llama3.2:latest`

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day39_Agentic_RAG_with_Embedding_Gemma
pip install -r requirements.txt
```

### Running the App

1. Pull required models for Ollama:

```bash
ollama pull embeddinggemma:latest
ollama pull llama3.2:latest
```

2. Start the Ollama server if not already running.
3. Launch the Streamlit app:

```bash
streamlit run agentic_rag_embeddinggemma.py
```

4. Open your browser at [http://localhost:8501](http://localhost:8501) to interact with the agent.

## 🧭 Real-World Use Cases

* Research assistants that summarize and answer questions from multiple PDFs.
* Corporate knowledge bases with private documents.
* Educational tools that provide AI tutoring using textbook PDFs.
* Legal or compliance document analysis.

## 📁 Repository Info

* **Project Name**: Agentic RAG with EmbeddingGemma
* **Day Number**: 25
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Agno, Streamlit, LanceDB, Ollama, EmbeddingGemma, Llama 3.2
* **License**: MIT
