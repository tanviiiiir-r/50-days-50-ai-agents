# 🧬 Multimodal AI Agent (Day 08) 💡

## Problem Section 💡

Analyzing videos and extracting actionable insights from them can be challenging, especially when combining visual content with external textual information. Users need an AI solution capable of understanding video content and integrating real-time web research for comprehensive answers.

## Solution Section 🚀

The Multimodal AI Agent leverages Google Gemini 2.5 to perform advanced video analysis and integrate web search results. Users can upload videos in various formats, and the agent processes the visuals while combining relevant information from web searches via DuckDuckGo, providing detailed and accurate answers.

## Features ⚙️

* Video analysis using Gemini 2.5 Flash/Pro.
* Web research integration through DuckDuckGo.
* Supports multiple video formats (MP4, MOV, AVI).
* Real-time video processing.
* Combined visual and textual analysis.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Models:** Google Gemini 2.5 Flash/Pro
* **Web Search Integration:** DuckDuckGo
* **Video Processing:** OpenCV / MoviePy
* **Environment Management:** API keys via environment variables

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* Google Gemini API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day08_Gemini_Multimodal_Agent
pip install -r requirements.txt
```

### Run Instructions

```bash
export GOOGLE_API_KEY=your_api_key_here
streamlit run multimodal_agent.py
```

## Real-World Use Cases 🧭

* Video content analysis for educational and research purposes.
* Generating insights from recorded lectures, meetings, or tutorials.
* Automated review of surveillance or event videos.
* Combining visual information with web research for comprehensive reports.

## Repository Info 📁

* **Project Name:** Multimodal AI Agent
* **Day Number:** 08
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/)
* **Tech Stack:** Streamlit, Gemini 2.5, DuckDuckGo, Python, OpenCV/MoviePy
* **License:** MIT
