# 📠 RAG Agent with Database Routing 🧩

## 💡 Problem

Users often need to query multiple data sources simultaneously. Traditional RAG systems may fail to route questions to the right database, leading to incomplete or inaccurate answers.

## 🚀 Solution

The **RAG Agent with Database Routing** uses an Agno agent to intelligently route natural language queries to specialized databases (Product Info, Customer Support & FAQ, Financial Info). If no relevant information is found, a LangGraph agent performs web research using DuckDuckGo, ensuring comprehensive answers.

## ⚙️ Features

* **Document Upload**: Add PDFs to Product Information, Customer Support & FAQ, or Financial Information databases
* **Natural Language Querying**: Automatic routing to the most relevant database
* **RAG Orchestration**: LangChain for retrieval-augmented generation
* **Fallback Mechanism**: LangGraph agent with DuckDuckGo search for unmatched queries
* **Multi-Database Support**: Efficient embedding storage and retrieval using Qdrant

## 🧠 Tech Stack

* LangChain (RAG orchestration)
* Agno Agent (Query router)
* LangGraph Agent (Fallback research)
* Qdrant (Vector database)
* Streamlit (Interactive UI)
* OpenAI (Language model for embeddings and query understanding)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* OpenAI API key
* Qdrant Cloud account

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day48_RAG_with_Database_Routing
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run rag_database_routing.py
```

### Configuration

1. Enter OpenAI API key in the application
2. Set up Qdrant Cloud cluster and provide API Key & URL
3. Upload PDF documents to the respective databases

## 🧭 Real-World Use Cases

* Enterprise knowledge management across multiple departments
* Customer support automation with fallback web search
* Financial reporting and analysis across structured and unstructured data
* Product information retrieval and FAQ answering

## 📁 Repository Info

* **Project Name**: RAG Agent with Database Routing
* **Day Number**: 48
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: LangChain, Agno, LangGraph, Qdrant, Streamlit, OpenAI
* **License**: MIT
