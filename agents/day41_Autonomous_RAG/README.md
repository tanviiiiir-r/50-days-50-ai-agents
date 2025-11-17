# 🤖 AutoRAG: Autonomous RAG with GPT-4o and Vector Database 🧠

## 💡 Problem

Many AI assistants cannot autonomously retrieve, integrate, and reason over user documents combined with web sources. Existing RAG systems often require manual setup and lack a unified interface for knowledge base and web search integration.

## 🚀 Solution

**AutoRAG** is an autonomous RAG system that allows users to upload PDF documents, add them to a persistent knowledge base, and query an AI assistant powered by GPT-4o. The system integrates web search with DuckDuckGo and stores conversation history for seamless, context-aware interactions.

## ⚙️ Features

* **Chat Interface**: Interact with the AI assistant naturally.
* **PDF Upload & Processing**: Add documents to the knowledge base for AI reference.
* **Knowledge Base Integration**: PostgreSQL with PgVector for efficient vector storage and retrieval.
* **Web Search Capability**: DuckDuckGo integration for real-time information.
* **Persistent Storage**: Conversations and assistant data are saved for future reference.

## 🧠 Tech Stack

* GPT-4o (OpenAI large language model)
* PostgreSQL with PgVector (Vector database)
* Streamlit (Web app interface)
* DuckDuckGo search API
* Python (Backend scripting and orchestration)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Docker (for PgVector)
* OpenAI API key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day41_Autonomous_RAG
pip install -r requirements.txt
```

### Running PgVector

```bash
docker run -d \
  -e POSTGRES_DB=ai \
  -e POSTGRES_USER=ai \
  -e POSTGRES_PASSWORD=ai \
  -e PGDATA=/var/lib/postgresql/data/pgdata \
  -v pgvolume:/var/lib/postgresql/data \
  -p 5532:5432 \
  --name pgvector \
  phidata/pgvector:16
```

### Running the App

```bash
streamlit run autorag.py
```

## 🧭 Real-World Use Cases

* Research assistants that query both local PDFs and web sources.
* Corporate knowledge management systems with searchable internal documentation.
* Legal or compliance teams referencing multiple documents and external regulations.
* Educational platforms that provide AI-guided learning from uploaded materials.

## 📁 Repository Info

* **Project Name**: AutoRAG: Autonomous RAG
* **Day Number**: 41
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: GPT-4o, PostgreSQL + PgVector, Streamlit, DuckDuckGo API
* **License**: MIT
