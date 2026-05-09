# 🔬 ResearchMind: Multi-Agent AI System

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_svg.svg)](YOUR_STREAMLIT_URL_HERE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-ff8c32.svg)](https://www.python.org/)
[![Mistral AI](https://img.shields.io/badge/Model-Mistral--Small-orange.svg)](https://mistral.ai/)

**ResearchMind** is a sophisticated multi-agent pipeline designed to transform a simple research topic into a structured, peer-reviewed report in seconds. By leveraging specialized AI agents, the system automates the tedious process of searching, filtering, reading, and synthesizing web data.

---

## ⚡ The Collaborative Pipeline

ResearchMind doesn't just "generate" text; it orchestrates a four-stage workflow where each step is handled by a specialized persona:

1.  **🔍 The Search Agent:** Uses the **Tavily API** to scan the live web for the most recent and relevant sources.
2.  **📄 The Reader Agent:** Navigates to the top-performing URLs and scrapes deep-page content for factual accuracy.
3.  **✍️ The Writer Chain:** Synthesizes gathered data into a professional, structured Markdown report.
4.  **🧐 The Critic Chain:** Critically evaluates the report, providing a score and specific areas for improvement.

---

## 🚀 Features

*   **Real-time Web Intelligence:** No "knowledge cut-off" — fetches data from 2025 and beyond.
*   **Deep Scraping:** Moves beyond search snippets to read actual article content.
*   **Self-Correction:** Integrated "Critic" loop ensures high-quality outputs.
*   **Beautiful UI:** A custom-styled, dark-mode Streamlit interface inspired by high-end research labs.
*   **Export Ready:** Download your final reports as clean Markdown files.

---

## 🛠️ Tech Stack

- **Orchestration:** [LangChain](https://www.langchain.com/)
- **LLM:** [Mistral AI](https://mistral.ai/) (`mistral-small-latest`)
- **Search Engine:** [Tavily AI](https://tavily.com/)
- **Frontend:** [Streamlit](https://streamlit.io/)
- **Package Manager:** [uv](https://github.com/astral-sh/uv) (for ultra-fast builds)

---