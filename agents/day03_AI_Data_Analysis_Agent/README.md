# 📊 AI Data Analysis Agent (Day 03) 💡

## Problem Section 💡

Analyzing data often requires SQL knowledge or expertise in data science tools, which can be a barrier for many users. Non-technical users struggle to derive insights from CSV or Excel files efficiently. There is a need for an AI-powered agent that makes data analysis accessible to everyone through natural language queries.

## Solution Section 🚀

The AI Data Analysis Agent empowers users to analyze their data files by translating natural language queries into SQL using GPT-4o, and processing them via DuckDB. It supports CSV and Excel uploads, automatically detects data types, and provides statistical summaries, visualizations, and actionable insights through an intuitive Streamlit interface.

## Features ⚙️

* 📤 **File Upload Support:** Upload CSV and Excel files with automatic schema inference.
* 💬 **Natural Language Queries:** Convert user questions into SQL queries for instant answers.
* 🔍 **Advanced Analysis:** Complex aggregations, filtering, sorting, statistical summaries, and visualizations.
* 🎯 **Interactive UI:** Streamlit-based interface for real-time query processing and clear results.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Model:** OpenAI GPT-4o
* **Database/Processing:** DuckDB for efficient SQL execution
* **Visualization:** Matplotlib / Seaborn / Plotly (as used in project)
* **Environment Management:** Streamlit session states for API keys

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* OpenAI API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day03_AI_Data_Analysis_Agent
pip install -r requirements.txt
```

### Run Instructions

```bash
streamlit run ai_data_analyst.py
```

## Real-World Use Cases 🧭

* Rapidly analyze business data without SQL expertise.
* Generate insights from sales, finance, or survey datasets.
* Visualize trends and distributions directly from uploaded files.
* Provide decision-makers with actionable summaries quickly.

## Repository Info 📁

* **Project Name:** AI Data Analysis Agent
* **Day Number:** 03
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/50-days-50-ai-agents/tree/main/agents/)
* **Tech Stack:** Streamlit, GPT-4o, DuckDB, Python
* **License:** MIT
