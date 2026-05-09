---
title: ResearchMind
emoji: 🔬
colorFrom: red
colorTo: pink
sdk: streamlit
app_file: main.py
pinned: false
---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=ResearchMind&fontSize=72&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Multi-Agent%20AI%20Research%20System&descAlignY=55&descSize=22" width="100%"/>

<br/>

[![Python](https://img.shields.io/badge/Python-3.11+-ff8c32?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![LangChain](https://img.shields.io/badge/LangChain-0.2+-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)](https://langchain.com)
[![Mistral AI](https://img.shields.io/badge/Mistral_AI-Small_2506-ff5a1a?style=for-the-badge&logoColor=white)](https://mistral.ai)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.x-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Tavily](https://img.shields.io/badge/Tavily-Search_API-0a0a0f?style=for-the-badge&logoColor=white)](https://tavily.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-50c878?style=for-the-badge)](LICENSE)

<br/>

> **Transform any topic into a polished, peer-reviewed research report — in seconds.**
> 
> *Four specialized AI agents. One seamless pipeline. Zero fluff.*

<br/>

<a href="YOUR_STREAMLIT_URL_HERE">
  <img src="https://static.streamlit.io/badges/streamlit_badge_black_white.svg" height="35"/>
</a>

<br/><br/>

---

</div>

## ✦ What is ResearchMind?

**ResearchMind** is not a chatbot. It's a **coordinated multi-agent system** — four purpose-built AI agents that collaborate like a research team, each owning a distinct phase of the knowledge pipeline:

```
  Topic Input
      │
      ▼
 ┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
 │  🔍 SEARCH  │────▶│  📄 READER  │────▶│  ✍️ WRITER  │────▶│  🧐 CRITIC  │
 │    AGENT    │     │    AGENT    │     │    CHAIN    │     │    CHAIN    │
 └─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
  Live web scan    Deep URL scraping    Structured report    Score + feedback
```

No knowledge cutoff. No hallucinated sources. Just **real data → real report**.

---

## ⚡ The Four-Stage Pipeline

<table>
<tr>
<td width="50">

**`01`**

</td>
<td width="60">🔍</td>
<td>

**Search Agent** — Armed with the **Tavily API**, it scans the live web and pulls the five most recent, reliable, and relevant sources on your topic. Real-time intelligence, not stale training data.

</td>
</tr>
<tr>
<td>

**`02`**

</td>
<td>📄</td>
<td>

**Reader Agent** — Goes beyond snippets. It autonomously picks the best URL from search results and **scrapes the full article** using BeautifulSoup, extracting up to 3,000 characters of deep-page content.

</td>
</tr>
<tr>
<td>

**`03`**

</td>
<td>✍️</td>
<td>

**Writer Chain** — Synthesizes everything into a **structured Markdown report** with Introduction, Key Findings, Conclusion, and cited Sources. Professional. Detailed. Ready to publish.

</td>
</tr>
<tr>
<td>

**`04`**

</td>
<td>🧐</td>
<td>

**Critic Chain** — Acts as a peer reviewer. Scores the report out of 10, highlights strengths, flags weak areas, and delivers a one-line verdict. Built-in quality control.

</td>
</tr>
</table>

---

## 🎯 Features at a Glance

| Feature | Detail |
|---|---|
| 🌐 **Live Web Intelligence** | Powered by Tavily — fetches data beyond any LLM's training cutoff |
| 🕷️ **Deep Content Scraping** | Moves past 300-char snippets to actual article body text |
| 🔄 **Self-Critiquing Loop** | Integrated critic scores every report before you see it |
| 🎨 **Premium Dark UI** | Custom-styled Streamlit with Syne + DM Sans typography |
| ⬇️ **One-Click Export** | Download finished reports as clean `.md` files instantly |
| 🧩 **Modular Architecture** | Each agent is independently swappable — plug in new LLMs or tools |
| 🚀 **Fast Setup** | Works with `uv` for near-instant dependency resolution |

---

## 🛠️ Tech Stack

```
┌─────────────────────────────────────────────────────────┐
│                    ResearchMind Stack                    │
├─────────────────┬───────────────────────────────────────┤
│  Orchestration  │  LangChain 0.2+                       │
│  LLM            │  Mistral AI  (mistral-small-2506)     │
│  Search         │  Tavily AI Search API                 │
│  Scraping       │  Requests + BeautifulSoup4            │
│  Frontend       │  Streamlit (custom CSS/dark theme)    │
│  Env Management │  python-dotenv                        │
│  Logging        │  Rich                                 │
│  Packaging      │  uv (ultra-fast) / pip                │
└─────────────────┴───────────────────────────────────────┘
```


## 🖼️ UI Preview

```
┌──────────────────────────────────────────────────────┐
│                                                      │
│         Multi-Agent AI System                        │
│                                                      │
│   Research Mind                                      │
│   ──────────────────────────────────────────         │
│   Four agents collaborate to deliver polished        │
│   research reports on any topic.                     │
│                                                      │
│  ┌────────────────────────────┐  Pipeline            │
│  │ Research Topic             │  ──────────          │
│  │ e.g. Quantum computing...  │  01 Search  ✓ DONE  │
│  └────────────────────────────┘  02 Reader  ✓ DONE  │
│  [ ⚡ Run Research Pipeline  ]   03 Writer  ● RUN…  │
│                                  04 Critic  WAITING  │
│                                                      │
└──────────────────────────────────────────────────────┘
```


## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

---