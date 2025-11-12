# 🔬 AI Domain Deep Research Agent 🧠

## 💡 Problem

Conducting deep research across multiple domains is time-consuming and requires access to diverse sources. Generating meaningful questions, gathering accurate information, and compiling professional reports often demands significant expertise and coordination.

## 🚀 Solution

The AI Domain Deep Research Agent automates comprehensive research by generating domain-specific questions, gathering information from multiple search engines, and compiling findings into a professional, McKinsey-style report. Integrated with Google Docs, it allows users to access and share research easily, all through an intuitive Streamlit interface.

## ⚙️ Features

* **Intelligent Question Generation**: Generates 5 domain-specific research questions focused on clear outcomes
* **Multi-Source Research**: Aggregates insights from Tavily Search, Perplexity AI, and other sources
* **Professional Report Generation**: Creates structured reports with executive summaries, analysis, and conclusions in Google Docs
* **User-Friendly Interface**: Streamlit UI with real-time progress tracking and expandable result sections

## 🧠 Tech Stack

* Python 3.10+
* Agno Agent Framework for orchestration
* Together AI Qwen 3 235B model for advanced language processing
* Composio tools for search integration and Google Docs export
* Streamlit for interactive UI

## 🧩 Setup Instructions

### Requirements

* Python 3.10 or higher
* Together AI API Key
* Composio API Key
* Internet connection for web search and Google Docs

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day14_AI_Deep_Research_Agent

# Install dependencies
pip install -r requirements.txt

# Add Composio tools
composio add googledocs
composio add perplexityai
```

### Environment Setup

* Store API keys in a `.env` file or input directly in the app sidebar

### Run Instructions

```bash
streamlit run ai_domain_deep_research_agent.py
```

Follow the on-screen interface to enter API keys, input your research topic, generate questions, conduct research, and compile the final report.

## 🧭 Real-World Use Cases

* Academic research across various disciplines
* Market and competitor analysis for businesses
* Policy research and historical analysis
* Technology evaluation and impact studies

## 📁 Repository Info

* **Project Name:** AI Domain Deep Research Agent
* **Day Number:** 14
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Agno, Together AI, Composio, Streamlit
* **License:** MIT
