# AI Teaching Agent Team 🧑‍🏫🤖

## Problem 💡

Learners and educators often spend excessive time assembling coherent curricula, curating high-quality resources, and designing meaningful practice — especially when personalization and progressive milestone planning are required. Fragmented content across blogs, papers, and tutorials makes it hard to create a unified, shareable learning package that scales for classrooms, bootcamps, or self-study.

This agent team exists to automate and standardize instructional design: producing a polished knowledge base, a milestone-driven learning roadmap, a curated resource library, and practice workbooks — all authored collaboratively by specialized AI teaching agents and exported to Google Docs for immediate sharing.

## Solution 🚀

**AI Teaching Agent Team** is a Streamlit application that orchestrates four specialist AI agents (Professor, Academic Advisor, Research Librarian, Teaching Assistant). Each agent writes its output to a separate Google Doc, producing a complete, editable learning bundle:

* A comprehensive knowledge base with headings, examples, and a table of contents.
* A timed, prerequisite-aware learning roadmap with milestones.
* A categorized, rated resource list (papers, tutorials, videos).
* A structured practice workbook with exercises and solution guides.

Agents coordinate to ensure alignment between curriculum content, learning milestones, resources, and practice — delivering a ready-to-use course pack in minutes.

## Features ⚙️

* **Professor Agent**: Generates a structured knowledge base (TOC, examples, concept explanations).
* **Academic Advisor Agent**: Builds a progressive roadmap with milestones, time estimates, and prerequisites.
* **Research Librarian Agent**: Curates and rates resources with short annotations and difficulty levels.
* **Teaching Assistant Agent**: Produces exercises, practice sections, and full solution guides.
* **Google Docs export** via Composio for easy collaboration and distribution.
* **Streamlit UI** for fast topic entry, API key management, and generation progress.
* Modular architecture — swap or extend agents for custom pedagogy or domain expertise.

## Tech Stack 🧠

* Python 3.10+
* Streamlit (UI)
* OpenAI API (LLM)
* Composio (Google Docs integration)
* SerpAPI (resource discovery)
* Libraries: `requests`, `python-dotenv`, `google-auth` (optional)

## Setup Instructions 🧩

### Requirements

* Python 3.10 or later
* pip
* OpenAI API key
* Composio API key (for Google Docs integration)
* SerpAPI key (recommended for richer resource discovery)
* (Optional) Virtual environment

### Installation

```bash
# Clone the 50 Days template repository (includes examples and structure)
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day30_ai_teaching_agent_team

# Recommended: create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.\.venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
```

> Note: the original demo repo is available at `https://github.com/Shubhamsaboo/awesome-llm-apps.git` — you may inspect the upstream implementation for reference.

### Configuration

Create a `.env` file in the project root or export the following environment variables:

```
OPENAI_API_KEY=sk-...
COMPOSIO_API_KEY=comp-...
SERPAPI_KEY=...
```

For Composio + Google Docs integration:

1. Create a Composio account and add the Google Docs connector (`composio add googledocs`).
2. Create an OAuth connection to your Google account within Composio and note the connection ID.
3. In Composio, open the Google Docs app and create an integration (use the UI "Create integration" / "Try connecting default's googledocs").

### Run instructions

```bash
streamlit run teaching_agent_team.py
```

In the Streamlit sidebar:

* Paste your OpenAI API key (or ensure `OPENAI_API_KEY` is set in your environment).
* Paste your Composio API key and confirm the Google Docs connection.
* (Optional) Paste your SerpAPI key for enhanced resource discovery.
* Enter the topic you want to learn (e.g., "Python Programming", "Machine Learning").
* Click **Generate Learning Plan** — each agent will run and create its own Google Doc. Links are shown in the app when finished.

## Real-World Use Cases 🧭

* **University lecturers**: Rapidly draft course modules and practice workbooks for a new semester.
* **Bootcamp organisers**: Generate standardized curricula, timelines, and exercises to distribute to instructors.
* **Self-learners**: Receive a personalized roadmap, curated reading list, and practice problems aligned to the knowledge base.
* **Corporate L&D teams**: Prototype upskilling tracks and distribute editable Google Docs to trainees.

## Repository Info 📁

* **Project Name:** AI Teaching Agent Team
* **Day Number:** Day 30
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, OpenAI API, Composio (Google Docs), SerpAPI
* **License:** MIT

---

**Quick clone:**

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
```
