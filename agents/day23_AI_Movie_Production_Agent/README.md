# 🎬 AI Movie Production Agent

## 💡 Problem

Creating a compelling movie involves significant effort in scriptwriting, casting, and conceptualization. Independent creators, production teams, and writers often face challenges in organizing ideas, generating engaging scripts, and identifying the right actors for their story.

## 🚀 Solution

The AI Movie Production Agent leverages Claude 3.5 Sonnet to automate the scriptwriting and casting process. By breaking down movie ideas into structured outlines, suggesting suitable actors, and providing a concise concept overview, the agent accelerates movie production planning and enables creators to focus on creativity and execution.

## ⚙️ Features

* **Script Generation**: Generates detailed outlines with character descriptions, plot points, and genre-specific elements
* **Actor Suggestion**: Recommends suitable actors based on past performances, availability, and target audience alignment
* **Movie Concept Overview**: Provides a clear, concise summary of the proposed movie, facilitating quick understanding and decision-making

## 🧠 Tech Stack

* Python
* Streamlit (UI)
* Claude 3.5 Sonnet (AI model)
* SerpAPI (actor and movie data search)

## 🧩 Setup Instructions

### Requirements

* Python 3.10 or higher
* Anthropic API key (Claude 3.5 Sonnet)
* SerpAPI key for web search

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day23_AI_Movie_Production_Agent

# Install dependencies
pip install -r requirements.txt
```

### Run Instructions

```bash
# Run the Streamlit app
streamlit run movie_production_agent.py
```

* Enter your Anthropic and SerpAPI keys when prompted
* Input your movie idea, genre, and target audience
* Receive a script outline, actor suggestions, and a concise movie concept overview

## 🧭 Real-World Use Cases

* Independent filmmakers planning script and casting
* Screenwriters seeking structured outlines
* Movie production teams accelerating pre-production planning
* Creative workshops generating story ideas and cast concepts

## 📁 Repository Info

* **Project Name:** AI Movie Production Agent
* **Day Number:** 23
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, Claude 3.5 Sonnet, SerpAPI
* **License:** MIT
