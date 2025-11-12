# 🥸 AI Meme Generator Agent - Browser Use (Day 05) 💡

## Problem Section 💡

Creating memes manually can be time-consuming and requires creativity and access to meme templates. Social media content creators, marketers, and casual users often need quick, humorous, or viral meme content without the hassle of manual design. There is a need for an AI-driven solution that automates meme generation efficiently.

## Solution Section 🚀

The AI Meme Generator Agent uses multi-LLM support and browser automation to create memes from text prompts. It interacts with meme websites, dynamically selects templates, inserts captions, and validates output quality. The system supports multiple AI models, ensuring creative, accurate, and shareable meme generation with minimal user effort.

## Features ⚙️

* **Multi-LLM Support:** Claude 3.5 Sonnet, GPT-4o, Deepseek v3 with automatic API validation and model switching.
* **Browser Automation:** Direct interaction with imgflip.com, automated template selection, dynamic caption insertion, and image link extraction.
* **Smart Generation Workflow:** Action verb extraction, metaphorical template matching, multi-step quality validation, and retry mechanism.
* **User-Friendly Interface:** Streamlit sidebar for model configuration, API key management, direct meme preview, and responsive error handling.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Models:** Claude 3.5 Sonnet, GPT-4o, Deepseek v3
* **Browser Automation:** Playwright
* **Environment Management:** API key handling via Streamlit session state

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* API keys for Anthropic (Claude), OpenAI (GPT-4o), and Deepseek

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day05_AI_Meme_Generator_Agent
pip install -r requirements.txt
python -m playwright install --with-deps
```

### Run Instructions

```bash
streamlit run ai_meme_generator_agent.py
```

## Real-World Use Cases 🧭

* Quickly generate memes for social media campaigns.
* Enhance online engagement with humorous AI-generated content.
* Automate meme creation for content scheduling and marketing purposes.
* Provide a creative tool for casual users and meme enthusiasts.

## Repository Info 📁

* **Project Name:** AI Meme Generator Agent - Browser Use
* **Day Number:** 05
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/)
* **Tech Stack:** Streamlit, Claude 3.5, GPT-4o, Deepseek v3, Playwright, Python
* **License:** MIT
