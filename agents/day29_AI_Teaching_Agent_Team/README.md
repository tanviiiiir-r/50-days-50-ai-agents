# AI Teaching Agent Team 🧑‍🏫🤖

## Problem 💡

Many learners struggle to assemble a coherent, practical learning path from scattered online resources. Teachers and self-learners waste time designing curricula, organising exercises, and curating reliable references — especially when they want a personalised, progressive plan that maps concepts to practice.

This agent team exists to automate the instructional design workflow: generate a structured knowledge base, a step-by-step learning roadmap, curated resources, and practice exercises — all produced collaboratively by specialised AI "teaching" agents and exported to Google Docs for easy sharing and collaboration.

## Solution 🚀

The **AI Teaching Agent Team** is a Streamlit application that runs four cooperative AI agents (Professor, Academic Advisor, Research Librarian, Teaching Assistant). Each agent handles a specific pedagogical responsibility and writes its output as a separate Google Doc. The result is a ready-to-use, shareable learning package: a knowledge base with TOC, a timed roadmap, a categorized resource library, and a practice workbook with solutions.

Agents coordinate automatically so the curriculum, resources, milestones, and exercises align with the learner's goals and prerequisites.

## Features ⚙️

* **Professor Agent**: Generates comprehensive lesson content with headings, examples, and a table of contents.
* **Academic Advisor Agent**: Produces a progressive learning roadmap with milestones, time estimates, and prerequisites.
* **Research Librarian Agent**: Curates papers, tutorials, and links with difficulty ratings and short annotations.
* **Teaching Assistant Agent**: Creates exercises and full solution guides organized into practice sections.
* Exports each agent's deliverable as an editable Google Doc for collaboration and distribution.
* Simple Streamlit UI to enter a topic and API credentials, then trigger generation.
* Modular design — agents can be extended or swapped for custom behaviour.

## Tech Stack 🧠

* Python (3.10+ recommended)
* Streamlit (web UI)
* OpenAI API (LLM)
* Composio (Google Docs integration)
* SerpAPI (web resource discovery)
* Standard Python libraries: `requests`, `google-auth` (if needed), `python-dotenv`

## Setup Instructions 🧩

### Requirements

* Python 3.10 or later
* pip (or an equivalent package manager)
* OpenAI API key
* Composio account & Composio API key (for Google Docs integration)
* SerpAPI key (optional but recommended for richer resource discovery)
* Optional: a virtual environment (venv / virtualenv / pipx)

### Installation

```bash
# Clone the official 50 Days repo (template + examples)
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git

cd 50-days-50-ai-agents/agents/day29_AI_Teaching_Agent_Team

# Create and activate a virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.\.venv\Scripts\activate  # Windows (PowerShell/CMD)

# Install Python dependencies
pip install -r requirements.txt
```

### Configuration

Create a `.env` file in the project root or export these environment variables:

```
OPENAI_API_KEY=sk-...
COMPOSIO_API_KEY=comp-...
SERPAPI_KEY=...
```

Notes:

* The Streamlit sidebar accepts keys directly if you prefer not to use environment variables.
* For Composio + Google Docs integration, follow the Composio documentation to create an OAuth connection and obtain a connection ID.

### Run instructions

```bash
streamlit run teaching_agent_team.py
```

Then in the Streamlit sidebar:

* Paste your OpenAI API key (or ensure `OPENAI_API_KEY` is set in the environment).
* Paste your Composio API key and complete the Google Docs connection step in Composio.
* (Optional) Paste your SerpAPI key for enhanced resource discovery.
* Enter the topic you want to learn and click **Generate Learning Plan**.

The app will show progress and provide links to the created Google Docs when generation completes.

## Real-World Use Cases 🧭

* **University lecturers** quickly draft course modules and supporting workbooks for a new semester.
* **Bootcamp organisers** generate a standardised curriculum, resources, timeline, and practice problems to share with instructors.
* **Self-learners** receive a personalised learning roadmap, curated reading list, and exercises that map directly to the knowledge base.
* **Corporate L&D teams** rapidly prototype upskilling plans and distribute editable Google Docs to trainees.

## Repository Info 📁

* **Project Name:** AI Teaching Agent Team
* **Day Number:** Day 12
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, OpenAI API, Composio (Google Docs integration), SerpAPI
* **License:** MIT

---

### Quick Links

* Clone template repo: `git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git`

---

