# 🔬 OpenAI Researcher Agent 🧠

## 💡 Problem

Conducting thorough research on any topic can be time-consuming and fragmented. Collecting accurate information, verifying sources, and compiling it into a well-organized report is often challenging, especially for users without advanced research skills.

## 🚀 Solution

The OpenAI Researcher Agent uses a multi-agent architecture to automate and streamline the research process. By leveraging OpenAI's Agents SDK, it coordinates specialized AI agents to gather, verify, and compile data into structured reports. Users can interact with an intuitive Streamlit interface to input research topics and receive comprehensive, source-cited reports.

## ⚙️ Features

* Multi-Agent Architecture:

  * **Triage Agent:** Plans research and coordinates workflow
  * **Research Agent:** Searches the web and gathers relevant information
  * **Editor Agent:** Compiles facts into a structured report
* Automatic fact collection with source attribution
* Structured report generation with titles, outlines, and citations
* Interactive Streamlit UI for easy input and real-time tracking
* Tracing and monitoring for full workflow visibility

## 🧠 Tech Stack

* Python 3.10+
* OpenAI Agents SDK
* Streamlit for interactive UI
* Web search APIs and data aggregation tools

## 🧩 Setup Instructions

### Requirements

* Python 3.10 or higher
* OpenAI API Key
* Internet connection for web research

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day12_OpenAI_Research_Agent

# Install dependencies
pip install -r requirements.txt
```

### Environment Setup

```bash
export OPENAI_API_KEY='your-api-key-here'
```

### Run Instructions

```bash
streamlit run openai_researcher_agent.py
```

Then open your web browser and navigate to the URL displayed (typically [http://localhost:8501](http://localhost:8501)) to interact with the OpenAI Researcher Agent.

## 🧭 Real-World Use Cases

* Academic research assistance for students and faculty
* Market research and competitive analysis for businesses
* Fact-checking and report generation for journalists
* Automated research workflow for content creators

## 📁 Repository Info

* **Project Name:** OpenAI Researcher Agent
* **Day Number:** 12
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, OpenAI Agents SDK, Streamlit, Web Search APIs
* **License:** MIT
