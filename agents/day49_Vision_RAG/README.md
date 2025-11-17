# Vision RAG with Cohere Embed-4 🖼️

## 💡 Problem

Processing and querying visual content from images and PDFs is challenging with standard text-based RAG systems. Users often need to understand charts, diagrams, or infographics directly without performing manual OCR or complex preprocessing.

## 🚀 Solution

Vision RAG leverages Cohere's Embed-4 for multimodal embeddings and Google Gemini 2.5 Flash for question answering. Users can upload images or PDFs, and the system retrieves the most relevant visual content, then generates accurate textual answers based on the visual context.

## ⚙️ Features

* **Multimodal Search**: Semantic search over images and PDF pages using Cohere Embed-4.
* **Visual Question Answering**: Gemini 2.5 Flash provides contextual answers based on the retrieved visual content.
* **Flexible Content Sources**: Supports sample images, custom image uploads, and PDF documents (processed page-wise).
* **No OCR Required**: Directly analyzes images and PDF pages.
* **Interactive UI**: Streamlit interface with content loading, question input, and result display.
* **Session Management**: Tracks loaded/uploaded content within a session.

## 🧠 Tech Stack

* **Cohere Embed-4**: For multimodal embeddings
* **Google Gemini 2.5 Flash**: For visual question answering
* **Streamlit**: Interactive web interface
* **PyMuPDF**: PDF page rendering
* **NumPy / SciPy**: For similarity search

## 🧩 Setup Instructions

### Requirements

* Python 3.8+
* Cohere API key
* Google Gemini API key

### Installation

1. Clone the repository:

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day49_Vision_RAG

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up API keys:

   * Cohere: [https://dashboard.cohere.com/api-keys](https://dashboard.cohere.com/api-keys)
   * Google: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

### Run Instructions

```bash
streamlit run vision_rag.py
```

Then open the provided local URL (usually `http://localhost:8501`) in your browser.

## 🧭 Real-World Use Cases

* Analyze financial charts and extract trends or figures.
* Answer questions about flowcharts, diagrams, or infographics in PDFs.
* Build visual knowledge bases for multi-page reports or presentations.
* Extract information from tables or screenshots without OCR.
* Perform quick analysis on research papers, reports, or presentations with mixed visual/text content.

## 📁 Repository Info

* **Project Name**: Vision RAG with Cohere Embed-4
* **Day Number**: 49
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Cohere Embed-4, Google Gemini 2.5 Flash, Streamlit, PyMuPDF, NumPy
* **License**: MIT
