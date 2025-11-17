# Voice RAG with OpenAI SDK 🎙️🤖

## Problem 💡

Users often struggle to extract meaningful answers from large PDF documents, manuals, or reports. Traditional search tools return static text results, and reading through lengthy content is time-consuming. Additionally, there is a lack of interactive, voice-enabled systems that can provide spoken responses for accessibility and convenience.

This agent exists to provide a **voice-enabled Retrieval-Augmented Generation (RAG)** system that allows users to query multiple documents, retrieve relevant content, and receive both text and high-quality speech answers in real time.

## Solution 🚀

The **Voice RAG with OpenAI SDK** system combines PDF processing, vector search, and TTS to deliver an interactive, voice-enabled knowledge interface:

* **Document Processing:** Uploaded PDFs are chunked and embedded using FastEmbed, then stored in a Qdrant vector database for efficient similarity search.
* **Query Processing:** User questions are converted into embeddings, relevant chunks are retrieved from Qdrant, and a processing agent formulates coherent, speech-friendly responses.
* **Voice Generation:** Responses are converted into natural-sounding speech via OpenAI TTS, supporting multiple voice personalities.

The system integrates a user-friendly Streamlit interface for uploading documents, asking questions, and listening to or downloading audio responses.

## Features ⚙️

* Multi-document PDF support with chunking and embedding
* Semantic search using Qdrant vector database
* Voice-enabled RAG with real-time TTS responses
* Multiple voice personalities for customization
* Streamlit interface for easy interaction
* Audio playback and MP3 download support
* Progress indicators for document processing and query handling
* Document source tracking for transparency

## Tech Stack 🧠

* Python 3.10+
* Streamlit (UI)
* OpenAI GPT-4o + TTS (text and speech generation)
* Qdrant (vector database)
* LangChain (RecursiveCharacterTextSplitter for document chunking)
* FastEmbed (embedding generation)
* Libraries: `requests`, `python-dotenv`

## Setup Instructions 🧩

### Requirements

* Python 3.10+
* pip
* OpenAI API key
* Qdrant Cloud account with API key
* Optional virtual environment

### Installation

```bash
# Clone repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day34_Voice_RAG_Agent

# Optional: create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run instructions

```bash
streamlit run rag_voice.py
```

### Usage

* Set API keys in `.env` file (OpenAI, Qdrant URL & key)
* Upload one or more PDF documents
* Ask questions via the Streamlit interface
* Listen to generated audio responses or download MP3 files
* Track document sources and monitor processing progress

## Real-World Use Cases 🧭

* **Enterprise knowledge bases**: Quickly answer employee questions from internal PDFs
* **Education**: Voice-enabled study assistants for textbooks or course materials
* **Accessibility**: Provide audio responses for visually impaired users
* **Research and legal analysis**: Retrieve and vocalize information from large document collections

## Repository Info 📁

* **Project Name:** Voice RAG with OpenAI SDK
* **Day Number:** Day 34
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, OpenAI GPT-4o + TTS, Qdrant, LangChain, FastEmbed
* **License:** MIT
