# 🌐 Web Scraping AI Agent 🤖

## 💡 Problem

Scraping websites manually is tedious and requires technical skills. Extracting relevant information efficiently from diverse websites can be challenging, especially when dealing with unstructured data.

## 🚀 Solution

The Web Scraping AI Agent uses OpenAI's LLMs (GPT-4o or GPT-5) combined with the scrapegraphai library to intelligently extract structured information from any website. Users simply provide a URL and specify the data they want, and the AI agent handles the rest, delivering clean, relevant results in an interactive Streamlit interface.

## ⚙️ Features

* Scrape any website by providing its URL
* Intelligent extraction using OpenAI LLMs
* Customize scraping tasks with user-defined prompts
* Interactive Streamlit UI for easy input and viewing
* Supports multiple language models (GPT-3.5-turbo, GPT-4, GPT-4o, GPT-5)

## 🧠 Tech Stack

* Python 3.10+
* OpenAI GPT-4/5 API
* scrapegraphai library for web scraping
* Streamlit for interactive UI

## 🧩 Setup Instructions

### Requirements

* Python 3.10 or higher
* OpenAI API Key
* Internet connection for web access

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day13_Web_Scrapping_AI_Agent

# Install dependencies
pip install -r requirements.txt
```

### Environment Setup

```bash
export OPENAI_API_KEY='your-api-key-here'
```

### Run Instructions

```bash
streamlit run ai_scrapper.py
```

Open your web browser and navigate to the displayed URL to use the Web Scraping AI Agent.

## 🧭 Real-World Use Cases

* Quickly extract product details from e-commerce websites
* Gather research data from multiple online sources
* Automate competitor website analysis
* Collect structured data from blogs, forums, and news sites

## 📁 Repository Info

* **Project Name:** Web Scraping AI Agent
* **Day Number:** 13
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, OpenAI GPT-4/5, scrapegraphai, Streamlit
* **License:** MIT
