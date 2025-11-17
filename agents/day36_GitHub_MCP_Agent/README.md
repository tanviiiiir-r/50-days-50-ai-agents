# Browser MCP Agent 🌐🤖

## Problem 💡

Automating web browsing and information extraction typically requires coding skills or complex scripting. Users struggle with multi-step navigation, interacting with page elements, and extracting meaningful insights without technical expertise.

The **Browser MCP Agent** allows anyone to control a browser using natural language commands, interact with web pages, extract content, and complete complex workflows effortlessly.

## Solution 🚀

This Streamlit application combines **Model Context Protocol (MCP)**, **MCP-Agent**, and **Playwright** to interpret natural language commands and execute them in a web browser:

* Navigate websites and interact with elements using plain English commands.
* Capture screenshots and provide visual feedback.
* Extract, summarize, and analyze webpage content.
* Perform multi-step tasks through conversation.

## Features ⚙️

* Natural language interface for browsing
* Full browser navigation and interaction
* Multi-step task execution
* Automated form filling, clicks, and scrolling
* Screenshot capture of webpage elements
* Content extraction and summarization
* Streamlit interface for real-time results
* OpenAI or Anthropic API integration for command interpretation

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
cd 50-days-50-ai-agents/examples/browser_mcp_agent

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

### Run Instructions

```bash
streamlit run main.py
```

### Usage

* Enter natural language commands in the Streamlit interface.
* Commands can include navigation, interaction, content extraction, and multi-step tasks.
* View results and screenshots in real time.

### Example Commands

* Navigation: "Go to [www.mcp-agent.com](http://www.mcp-agent.com)", "Go back to the previous page"
* Interaction: "Click on the login button", "Scroll down to see more content"
* Content Extraction: "Summarize the main content of this page", "Extract navigation menu items", "Take a screenshot of the hero section"
* Multi-step Tasks: "Go to the blog, find the most recent article, and summarize its key points"

## Real-World Use Cases 🧭

* Automate website data extraction for research and analytics
* Quickly summarize competitor content
* Automate repetitive web tasks like form submission or navigation
* Build interactive demos or prototypes with natural language browsing

## Repository Info 📁

* **Project Name:** Browser MCP Agent
* **Day Number:** Day 35
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, MCP, MCP-Agent, Playwright, OpenAI/Anthropic, Node.js
* **License:** MIT
