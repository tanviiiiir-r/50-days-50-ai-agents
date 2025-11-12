# 🚀 AI Product Launch Intelligence Agent

## 💡 Problem

Product marketing and GTM teams often struggle to gather, organize, and analyze scattered public-web information for new product launches. Tracking competitor moves, market sentiment, and KPIs in real-time is labor-intensive and prone to missed insights.

## 🚀 Solution

The AI Product Launch Intelligence Agent consolidates public data into concise, actionable insights. By combining GPT-4o with Firecrawl and a multi-agent coordinated approach, it provides structured competitor analysis, market sentiment evaluation, and launch metrics, enabling smarter, faster, and more informed decisions.

## ⚙️ Features

* Evidence-backed competitor analysis with launch positioning, pricing, and channels
* Market sentiment analysis (positive vs. negative drivers)
* Publicly available launch metrics tracking (KPIs, adoption, press coverage)
* Secure API key input via sidebar or `.env`
* Coordinated multi-agent team (Product Analyst, Market Sentiment Specialist, Launch Metrics Specialist)
* Quick keyboard shortcuts (J/K/L) to trigger analyses
* Auto-formatted Markdown reports
* Sources section listing crawled URLs for transparency

## 🧠 Tech Stack

* Python
* Streamlit (UI)
* OpenAI GPT-4o
* Agno AI Agent Framework
* Firecrawl (async search + crawl API)

## 🧩 Setup Instructions

### Requirements

* Python 3.10 or higher
* OpenAI API key
* Firecrawl API key

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day19_AI_Product_Launch_Intelligence_Agent

# Install dependencies
pip install -r requirements.txt
```

### Run Instructions

```bash
# Run the Streamlit app
streamlit run product_launch_intelligence_agent.py
```

* Enter API keys via sidebar or `.env`
* Input company/product/hashtag
* Navigate tabs and analyze

## 🧭 Real-World Use Cases

* GTM teams tracking competitor product launches
* Marketing teams monitoring social sentiment and public reactions
* Product managers evaluating launch KPIs
* Analysts generating automated launch reports

## 📁 Repository Info

* **Project Name:** AI Product Launch Intelligence Agent
* **Day Number:** 19
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, GPT-4o, Agno AI Agent Framework, Firecrawl
* **License:** MIT
