# Browser MCP Agent 🌐🤖

## Problem 💡

Navigating websites programmatically typically requires coding skills or complex automation scripts. Users struggle to complete multi-step browsing tasks or extract information quickly using traditional tools. There is also limited support for voice or natural language-based web interactions.

The **Browser MCP Agent** solves this problem by enabling users to control a browser using natural language commands, interact with web elements, extract content, and complete complex tasks without writing code.

## Solution 🚀

This Streamlit application leverages **Model Context Protocol (MCP)**, **MCP-Agent**, and **Playwright** to allow natural language-driven web automation:

* **Natural Language Interface:** Execute browsing commands in plain English.
* **Full Browser Navigation:** Navigate websites, click links, and go back/forward.
* **Interactive Elements:** Fill forms, click buttons, scroll, and complete multi-step tasks.
* **Visual Feedback:** Capture screenshots of web elements or sections.
* **Information Extraction:** Summarize page content or extract specific components.

Users interact through a Streamlit interface, receiving real-time results and screenshots while completing sophisticated browsing workflows.

## Features ⚙️

* Natural language control for browser navigation and interaction
* Multi-step task execution via conversation
* Form filling, button clicks, and scrolling automation
* Webpage screenshots for visual confirmation
* Content extraction and summarization
* Streamlit interface with live results
* OpenAI or Anthropic API integration for LLM-driven command interpretation

## Tech Stack 🧠

* Python 3.8+
* Streamlit (UI)
* MCP (Model Context Protocol)
* MCP-Agent (Agentic Framework)
* Playwright (browser automation)
* OpenAI / Anthropic API
* Node.js and npm (required by Playwright)

## Setup Instructions 🧩

### Requirements

* Python 3.8+
* Node.js and npm
* OpenAI or Anthropic API Key

### Installation

```bash
# Clone repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day35_Browser_MCP_Agent
# Install dependencies
pip install -r requirements.txt

# Verify Node.js and npm
node --version
npm --version
```

### Configure API Key

```bash
export OPENAI_API_KEY='your-openai-api-key'
```

### Run instructions

```bash
streamlit run main.py
```

### Usage

* Enter natural language commands in the Streamlit interface
* Commands can include navigation, interaction, content extraction, and multi-step sequences
* View results and screenshots in real time

### Example Commands

* Navigation: "Go to [www.mcp-agent.com](http://www.mcp-agent.com)", "Go back to the previous page"
* Interaction: "Click on the login button", "Scroll down to see more content"
* Content Extraction: "Summarize the main content of this page", "Extract navigation menu items", "Take a screenshot of the hero section"
* Multi-step Tasks: "Go to the blog, find the most recent article, and summarize its key points"

## Real-World Use Cases 🧭

* Automate website data extraction for research or analytics
* Summarize competitor content quickly
* Automate repetitive web tasks such as form submission or navigation
* Build demos or prototypes using conversational web control

## Repository Info 📁

* **Project Name:** Browser MCP Agent
* **Day Number:** Day 35
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, MCP, MCP-Agent, Playwright, OpenAI/Anthropic, Node.js
* **License:** MIT
