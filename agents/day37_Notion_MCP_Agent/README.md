# Notion MCP Agent 📑🤖

## Problem 💡

Interacting with Notion pages programmatically often requires coding knowledge and multiple API calls. Users struggle to perform updates, retrieve information, or manage complex page structures efficiently. There’s also a need for natural language interaction and context-aware conversation with Notion content.

## Solution 🚀

**Notion MCP Agent** allows users to interact with Notion pages using natural language commands in a terminal interface. It connects to the **Notion MCP server** and uses OpenAI for understanding and executing commands. Users can create, update, retrieve, and manage content efficiently while maintaining multi-turn conversational context.

## Features ⚙️

* Natural language terminal interface for Notion
* Update, insert, and retrieve page content
* Create and edit blocks, lists, tables, and other structures
* Add comments to blocks
* Search for specific information
* Maintains conversation context for multi-turn interactions
* Session management for persistent conversations

## Tech Stack 🧠

* Python 3.10+
* OpenAI API (LLM for natural language commands)
* Notion API via Notion MCP server
* Terminal CLI interface

## Setup Instructions 🧩

### Prerequisites

* Python 3.10+
* Notion account with admin permissions
* Notion Integration Token
* OpenAI API Key

### Installation

```bash
# Clone repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day37_Notion_MCP_Agent

# Install dependencies
pip install -r requirements.txt
```

### Notion Integration Setup

1. Create a Notion Integration: [Notion Integrations](https://www.notion.so/my-integrations)

   * Enable Read & Write content
   * Copy your Internal Integration Token

2. Share your Notion page with the integration:

   * Use the three dots (⋮) → Add connections → Select your integration
   * OR use the Share button → search for integration → Invite

3. Find your Notion Page ID:

   * Open your Notion page in a browser
   * Copy the URL and extract the part after the last dash

### Configuration

Set environment variables:

```bash
export NOTION_API_KEY='your-notion-api-key'
export OPENAI_API_KEY='your-openai-api-key'
export NOTION_PAGE_ID='your-page-id'
```

## Run Instructions

```bash
# Start agent
python notion_mcp_agent.py

# Or provide page ID directly
python notion_mcp_agent.py your-page-id-here
```

### Conversation Flow

* Creates unique user ID and session ID per run
* Maintains multi-turn conversation context
* Exit anytime by typing: `exit`, `quit`, `bye`, `goodbye`

## Example Queries

* "What's on my Notion page?"
* "Add a new paragraph saying 'Meeting notes for today'"
* "Create a bullet list with three items: Apple, Banana, Orange"
* "Add a comment to the first paragraph saying 'This looks good!'"
* "Search for any mentions of meetings"
* "Summarize our conversation so far"

## Real-World Use Cases 🧭

* Quickly update Notion pages without navigating the UI
* Keep meeting notes and summaries organized via natural language
* Manage to-do lists, tables, and content blocks efficiently
* Automate content retrieval and reporting

## Repository Info 📁

* **Project Name:** Notion MCP Agent
* **Day Number:** Day 36
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, OpenAI API, Notion MCP, Terminal CLI
* **License:** MIT
