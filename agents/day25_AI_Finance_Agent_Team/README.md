# 💲 AI Finance Agent Team with Web Access

## 💡 Problem

Financial analysis requires gathering data from multiple sources, evaluating trends, and making informed decisions quickly. Manual research is time-consuming, prone to errors, and difficult to scale for real-time insights.

## 🚀 Solution

The AI Finance Agent Team provides a multi-agent system that automates financial research and analysis. Using GPT-4o, the system combines web search capabilities with financial data analytics to deliver comprehensive insights efficiently. Specialized agents coordinate seamlessly to provide high-quality financial recommendations.

## ⚙️ Features

* Multi-agent system with specialized roles:

  * **Web Agent** for general internet research
  * **Finance Agent** for detailed financial analysis
  * **Team Agent** for coordinating between agents
* Real-time financial data access through **YFinance**
* Web search capabilities using **DuckDuckGo**
* Persistent storage of agent interactions using **SQLite**

## 🧠 Tech Stack

* Python 3.10+
* OpenAI GPT-4o
* YFinance
* DuckDuckGo search API
* SQLite
* Flask or Streamlit (for playground interface)

## 🧩 Setup Instructions

### Requirements

* OpenAI API Key
* Python 3.10 or above

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day25_AI_Finance_Agent_Team

# Install dependencies
pip install -r requirements.txt
```

### Configuration

```bash
# Set your OpenAI API key as an environment variable
export OPENAI_API_KEY='your-api-key-here'
```

### Run Instructions

```bash
python3 finance_agent_team.py
```

* Open your web browser and navigate to the URL provided in the console to interact with the AI Finance Agent Team.

## 🧭 Real-World Use Cases

* Automated stock market analysis and recommendations
* Portfolio risk assessment and optimization
* Financial news summarization for decision making
* Real-time trend monitoring for investors and analysts

## 📁 Repository Info

* **Project Name:** AI Finance Agent Team with Web Access
* **Day Number:** 25
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, GPT-4o, YFinance, DuckDuckGo, SQLite
* **License:** MIT
