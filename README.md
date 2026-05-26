# LLM Arbitration System

Multi-agent AI evaluation framework where multiple specialized critic agents independently audit LLM-generated outputs for factual accuracy, logical consistency, and completeness before an adjudicator synthesizes a confidence-scored final verdict.

---

## Architecture

User Prompt
    ↓
LLM Output
    ↓
Parallel Critic Agents
    ├── Factual Accuracy Critic
    ├── Logical Consistency Critic
    └── Completeness Critic
    ↓
Disagreement Detection
    ↓
Adjudicator Agent
    ↓
Final Verdict + Confidence Score

---

## Features

- Multi-agent evaluation pipeline
- Parallel critique orchestration using LangGraph
- Structured outputs using Pydantic
- Multi-provider arbitration (OpenAI, Anthropic, Ollama)
- Confidence-scored verdict synthesis
- FastAPI inference API
- Analytics dashboard for critic disagreement analysis
- Dockerized deployment

---

## Tech Stack

- Python
- LangGraph
- FastAPI
- OpenAI API
- Anthropic API
- Ollama
- Pydantic
- SQLite
- Streamlit

---

## Status

🚧 In Active Development
