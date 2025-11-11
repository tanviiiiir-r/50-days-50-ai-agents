# 📰 ➡️ 🎙️ Blog to Podcast Agent

Turn any blog post into a **podcast episode** in minutes — powered by GPT-4, Firecrawl, and ElevenLabs.
This AI Agent reads your favorite blogs, summarizes them intelligently, and converts them into high-quality, natural-sounding audio — bringing written content to life.

---

## 💡 Problem

In today's content-heavy world, not everyone has time to read long blogs. Many professionals prefer **listening on the go** — during commutes, workouts, or breaks.
However, most blogs are only available in text format, leaving a gap between **written information** and **audio accessibility**.

---

## 🚀 Solution

The **Blog to Podcast Agent** solves this by automatically turning any blog post into an engaging podcast episode.
With a single URL, it:

1. Scrapes the full blog content using **Firecrawl**.
2. Summarizes it smartly using **GPT-4** (under 2000 characters).
3. Converts that summary into a natural podcast voice using **ElevenLabs**.

This bridges reading and listening — making online knowledge portable, accessible, and enjoyable.

---

## ⚙️ Features

✅ **Blog Scraping** — Extracts complete content from any public blog via Firecrawl API.
✅ **AI Summarization** — Uses GPT-4 to create concise, listener-friendly summaries.
✅ **Podcast Generation** — Transforms text into realistic audio using ElevenLabs.
✅ **Secure API Handling** — All API keys are entered locally in Streamlit’s sidebar.

---

## 🧠 Tech Stack

* **Streamlit** — Interactive app interface
* **OpenAI GPT-4** — Blog summarization
* **Firecrawl API** — Blog scraping
* **ElevenLabs API** — Text-to-speech podcast generation
* **Python 3.8+**

---

## 🧩 Setup Instructions

### 1. Requirements

You’ll need the following API keys:

* **OpenAI API Key** → [Get one here](https://platform.openai.com)
* **ElevenLabs API Key** → [Get one here](https://elevenlabs.io)
* **Firecrawl API Key** → [Get one here](https://firecrawl.dev)
* Ensure **Python 3.8+** is installed.

---

### 2. Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents
cd 50-days-50-ai-agents/agents/day01_blog_to_podcast_agent

# Install dependencies
pip install -r requirements.txt
```

---

### 3. Run the App

```bash
streamlit run blog_to_podcast_agent.py
```

Once the app launches:

1. Enter your **API keys** in the sidebar.
2. Paste your **blog URL**.
3. Click **🎙️ Generate Podcast**.
4. Listen or download your podcast instantly.

---

## 🧭 Real-World Use Cases

* **Writers & Bloggers** — Expand audience reach by offering an audio version of blogs.
* **Podcasters** — Quickly create fresh content from trending articles.
* **Students & Professionals** — Learn faster by listening to summaries of important blogs.
* **Accessibility** — Helps visually impaired users access written knowledge easily.

---

## 📁 Repository Info

**🧠 Project Name:** Blog to Podcast Agent
**📅 Day:** 01
**📚 Series:** 50 Days, 50 AI Agents
**👨‍💻 Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
**🛠 Tech Stack:** Python, Streamlit, GPT-4, Firecrawl, ElevenLabs
**📜 License:** MIT

---

✨ *Part of the “50 Days, 50 AI Agents” journey — building one high-value AI project every day.*
