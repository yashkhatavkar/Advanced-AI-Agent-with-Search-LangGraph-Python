# Advanced-AI-Agent-with-Search-LangGraph-Python

A lightweight web-research agent that:
- runs multi-step workflows with **LangGraph**
- searches the web (Google/Bing/Reddit) and/or **Bright Data Datasets**
- ranks, dedupes, and summarizes results with an LLM
- outputs sources and a concise brief

## Quickstart
```bash
# 1) Setup
python -m venv .venv && . .venv/Scripts/activate  # (Windows Git Bash) 
pip install -r requirements.txt

# 2) Configure
cp .env.example .env  # then fill in keys

# 3) Run
python main.py "your research question"
