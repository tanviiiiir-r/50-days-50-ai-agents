# 🧐 Agentic RAG with Reasoning 🤖

## 💡 Problem

AI systems often provide answers without showing their thought process, leaving users uncertain about reliability and context. Existing RAG systems typically retrieve information but lack transparency in reasoning steps, making it hard to trust complex outputs.

## 🚀 Solution

This project demonstrates an **agentic RAG system with transparent reasoning**. Using Agno, Gemini 2.5 Flash, and OpenAI embeddings, users can dynamically add web sources, ask questions, and observe the agent's step-by-step thinking in real-time. The system provides source citations, session tracking, and semantic search for accurate, verifiable answers.

## ⚙️ Features

* **Interactive Knowledge Base Management**:

  * Add URLs dynamically for web content
  * Default knowledge source: MCP vs A2A Protocol article
  * Persistent vector storage with LanceDB
  * Session state tracking to avoid duplicate loading

* **Transparent Reasoning Process**:

  * Real-time display of the agent's thought steps
  * Side-by-side view of reasoning and final answers
  * Clear visibility into the RAG pipeline

* **Advanced RAG Capabilities**:

  * Vector search using OpenAI embeddings
  * Source attribution with citations

## 🧠 Tech Stack

* Agno v2.0 (AI agent framework)
* Gemini 2.5 Flash (Language processing)
* OpenAI Embeddings (Vector search)
* LanceDB (Vector database)
* Streamlit (Web interface)
* ReasoningTools (Step-by-step analysis)

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Google API Key
* OpenAI API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day40_Agentic_RAG_with_Reasoning
pip install -r requirements.txt
```

### Running the App

1. Launch the Streamlit app:

```bash
streamlit run rag_reasoning_agent.py
```

2. Enter your API keys in the provided fields.
3. Use the sidebar to add or manage knowledge sources.
4. Ask questions using the main input field.
5. Observe the agent's reasoning in the left panel and answers with citations in the right panel.

## 🧭 Real-World Use Cases

* Educational tools that explain step-by-step reasoning for queries.
* Transparent AI research assistants for complex topics.
* Legal or technical document analysis with traceable citations.
* Corporate knowledge management with dynamic web source integration.

## 📁 Repository Info

* **Project Name**: Agentic RAG with Reasoning
* **Day Number**: 26
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Agno, Gemini 2.5 Flash, OpenAI Embeddings, LanceDB, Streamlit, ReasoningTools
* **License**: MIT
