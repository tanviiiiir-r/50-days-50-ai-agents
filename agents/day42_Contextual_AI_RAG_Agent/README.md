# 🌐 Contextual AI RAG Agent 🤖

## 💡 Problem

Creating a retrieval-grounded AI assistant often requires complex setup and infrastructure. Users need a seamless way to ingest documents, manage knowledge stores, and generate accurate AI responses that are faithful to the underlying data.

## 🚀 Solution

The **Contextual AI RAG Agent** provides a Streamlit-based interface to easily integrate with Contextual AI's managed RAG platform. Users can create datastores, ingest documents, spin up agents, and chat with AI grounded on their data. Features like retrieval visualization, multilingual reranking, and LMUnit evaluation ensure transparency and high-quality answers.

## ⚙️ Features

* **Document Ingestion**: Upload PDFs or text files to Contextual AI datastores.
* **Agent Management**: Create or use existing agents linked to one or more datastores.
* **Grounded Responses**: Generate answers via Contextual’s Grounded Language Model (GLM).
* **Reranking**: Rank retrieved documents by relevance and custom instructions, supporting multilingual queries.
* **Retrieval Visualization**: Show attribution page images and metadata.
* **Answer Evaluation**: LMUnit evaluation using custom rubrics for quality assessment.

## 🧠 Tech Stack

* Contextual AI Managed RAG Platform
* Streamlit (Web app interface)
* GLM (Grounded Language Model)
* Python

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Contextual AI account and API key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day42_Contextual_AI_RAG_Agent
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run contextualai_rag_agent.py
```

### API Key Configuration

1. Log in to your Contextual AI tenant at `app.contextual.ai`.
2. Navigate to **API Keys** → **Create API Key**.
3. Paste the API key in the app sidebar.

## 🧭 Real-World Use Cases

* Corporate knowledge management with retrieval-grounded AI assistants.
* Legal and compliance document querying.
* Research assistants for educational or scientific materials.
* Multilingual information retrieval and evaluation.

## 📁 Repository Info

* **Project Name**: Contextual AI RAG Agent
* **Day Number**: 42
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Contextual AI, Streamlit, GLM, Python
* **License**: MIT
