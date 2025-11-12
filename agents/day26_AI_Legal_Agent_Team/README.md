# 👨‍⚖️ AI Legal Agent Team

## 💡 Problem

Legal document review and strategic planning require specialized knowledge, meticulous research, and thorough analysis. Manual legal analysis is time-consuming, error-prone, and difficult to scale, especially for law firms or corporate legal departments handling large volumes of contracts and legal documents.

## 🚀 Solution

The AI Legal Agent Team automates legal analysis by combining multiple AI agents, each specialized in a particular legal role. From contract review to risk assessment and strategic planning, the system provides accurate, sourced, and actionable insights efficiently. The agents collaborate seamlessly to mimic a full-service legal team.

## ⚙️ Features

* **Specialized Legal AI Agent Team:**

  * **Legal Researcher**: Uses DuckDuckGo for legal case research, cites sources, and references document sections.
  * **Contract Analyst**: Performs detailed contract reviews, identifies obligations, and flags potential issues.
  * **Legal Strategist**: Develops comprehensive strategies and actionable recommendations considering risks and opportunities.
  * **Team Lead**: Coordinates analysis, ensures thorough and sourced recommendations, and manages collaboration between agents.
* **Document Analysis Types:**

  * Contract Review
  * Legal Research
  * Risk Assessment
  * Compliance Check
  * Custom Queries

## 🧠 Tech Stack

* Python 3.10+
* Streamlit
* OpenAI GPT-4o
* Qdrant (for embeddings and vector database)
* DuckDuckGo API
* PDF document processing libraries

## 🧩 Setup Instructions

### Requirements

* OpenAI API Key
* Qdrant API Key and URL
* Python 3.10 or above

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day26_AI_Legal_Agent_Team

# Install dependencies
pip install -r requirements.txt
```

### Configuration

* Obtain OpenAI API key and Qdrant API key/URL
* Set environment variables or enter them via the interface

### Run Instructions

```bash
streamlit run legal_agent_team.py
```

* Upload a PDF document
* Choose analysis type
* Add custom queries if needed
* View results in the Streamlit interface

## 🧭 Real-World Use Cases

* Automated contract review for law firms or corporate legal teams
* Risk assessment for legal compliance
* Legal research for case preparation or due diligence
* Compliance checks for regulatory requirements
* Custom legal queries for advisory services

## 📁 Repository Info

* **Project Name:** AI Legal Agent Team
* **Day Number:** 26
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, GPT-4o, Qdrant, DuckDuckGo, PDF processing
* **License:** MIT
