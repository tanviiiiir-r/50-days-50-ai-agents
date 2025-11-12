# 📈 AI Startup Trend Analysis Agent (Day 09) 💡

## Problem Section 💡

Identifying emerging startup trends and market opportunities can be challenging for entrepreneurs due to the vast amount of scattered information online. Manual research is time-consuming, and missing key insights can lead to missed opportunities. There is a need for an AI tool that consolidates information, highlights trends, and provides actionable insights efficiently.

## Solution Section 🚀

The AI Startup Trend Analysis Agent uses Claude 3.5 Sonnet, Newspaper4k, and DuckDuckGo to automate trend research. Entrepreneurs can input sectors or technologies of interest, and the agent collects startup news, funding data, and market insights. It generates concise summaries, detects emerging patterns, and highlights growth opportunities, helping users make data-driven decisions.

## Features ⚙️

* **User Prompt:** Input startup sectors or technologies for targeted research.
* **News Collection:** Gather recent startup news, funding rounds, and market analysis via DuckDuckGo.
* **Summary Generation:** Use Newspaper4k to create concise, verified summaries.
* **Trend Analysis:** Identify emerging patterns in funding, technology adoption, and market opportunities.
* **Streamlit UI:** User-friendly interface for seamless interaction.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Models:** Claude 3.5 Sonnet (Anthropic)
* **Web Scraping:** Newspaper4k, DuckDuckGo
* **Environment Management:** Virtual environment, API keys via Streamlit sidebar

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* Anthropic API Key (Claude 3.5 Sonnet)

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day09_AI_Startup_Trend_Analysis_Agent
python -m venv venv
source venv/bin/activate  # macOS/Linux
# .\venv\Scripts\activate  # Windows
pip install -r requirements.txt
```

### Run Instructions

```bash
streamlit run startup_trends_agent.py
```

## Real-World Use Cases 🧭

* Validate startup ideas with data-driven insights.
* Monitor emerging trends in funding and technology adoption.
* Identify untapped market opportunities for early-stage ventures.
* Generate summaries of startup-related news for quick decision-making.

## Repository Info 📁

* **Project Name:** AI Startup Trend Analysis Agent
* **Day Number:** 09
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/)
* **Tech Stack:** Streamlit, Claude 3.5 Sonnet, Newspaper4k, DuckDuckGo, Python
* **License:** MIT
