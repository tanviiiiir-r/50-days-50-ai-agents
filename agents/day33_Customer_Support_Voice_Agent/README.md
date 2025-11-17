# Customer Support Voice Agent 🎙️🤖

## Problem 💡

Many organizations struggle to provide fast, accurate, and engaging responses to user queries across complex documentation. Traditional chat or FAQ systems often require users to read long pages, leading to slower issue resolution and lower user satisfaction. Static text responses also lack personalization and natural delivery, reducing accessibility.

This agent exists to convert documentation into an interactive, voice-enabled knowledge base, delivering both text and speech responses to user questions with natural intonation, multiple voice options, and semantic search capabilities.

## Solution 🚀

The **Customer Support Voice Agent** leverages OpenAI SDK, TTS, and a vector search-based knowledge base to create a voice-first support experience:

* **Knowledge Base Creation**: Crawls documentation websites using Firecrawl, processes content, generates embeddings via FastEmbed, and stores them in a Qdrant vector database for semantic search.
* **AI Agent Team**:

  * **Documentation Processor**: Analyzes content and generates clear, concise responses.
  * **TTS Agent**: Converts text responses into natural-sounding speech with multiple voice options.
  * **Voice Customization**: Supports voices like alloy, ash, ballad, coral, echo, fable, onyx, nova, sage, shimmer, verse.
* **Interactive Interface**: Streamlit UI with real-time query handling, sidebar configuration, audio player, and progress indicators.

Users input a documentation URL, select a voice, and can interactively ask questions, receiving immediate textual and audio responses.

## Features ⚙️

* Automated documentation crawling and knowledge base creation
* Semantic search and fast content retrieval using embeddings and Qdrant
* Multiple AI agents coordinating content processing and voice synthesis
* Expressive text-to-speech output with customizable voices
* Real-time interactive Streamlit interface
* Audio playback and download capabilities
* Support for multiple documentation pages (default: 5 pages)

## Tech Stack 🧠

* Python 3.10+
* Streamlit (UI)
* OpenAI GPT-4o + TTS
* Firecrawl (documentation crawling)
* Qdrant (vector database for semantic search)
* FastEmbed (embedding generation)
* Libraries: `requests`, `python-dotenv`, `qdrant-client`

## Setup Instructions 🧩

### Requirements

* Python 3.10+
* pip
* API keys for OpenAI, Qdrant, and Firecrawl
* Optional virtual environment

### Installation

```bash
# Clone repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day33_Customer_Support_Voice_Agent

# Optional: create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run instructions

```bash
streamlit run ai_voice_agent_docs.py
```

### Usage

* Enter API keys in the sidebar (OpenAI, Qdrant, Firecrawl)
* Input the documentation URL
* Select preferred voice
* Initialize the system to process documentation
* Ask questions and receive text and voice responses

## Real-World Use Cases 🧭

* **Customer support teams**: Provide instant, voice-based answers from documentation.
* **Software documentation portals**: Enhance user engagement with TTS-powered guidance.
* **Internal knowledge bases**: Enable employees to query complex manuals quickly.
* **Accessible learning**: Support visually impaired users with high-quality audio answers.

## Repository Info 📁

* **Project Name:** Customer Support Voice Agent
* **Day Number:** Day 33
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, OpenAI GPT-4o + TTS, Firecrawl, Qdrant, FastEmbed
* **License:** MIT
