# RAG-Powered Customer Support Chatbot

This repository demonstrates a practical Retrieval-Augmented Generation (RAG) pipeline for reliable, document-grounded customer support. The bot finds relevant content in a knowledge base and uses that as evidence to create clear, helpful answers.

## Purpose

Stop “hallucination” and ensure answers are grounded in source documents so support agents and customers get fact-based, verifiable responses.

## Typical Tech Stack

- Python: implementation
- OpenAI: embeddings and GPT generation
- LangChain: optional orchestration
- vector DB: efficient similarity search
- Jupyter: interactive examples


## What’s in this repo

| File | Purpose |
| :--- | :--- |
| `notebook.ipynb` | Guided notebook showing the RAG pipeline |
| `knowledge_base.csv` | Example support docs or FAQs |
| `knowledge_embeddings.json` | Precomputed embeddings |
| `predefined_responses.json` | Fallback messages |
| `chatbot_responses.json` | Sample outputs / logs |
| `processed_queries.csv` | Query logs and metrics |


## Quick Start

Clone the repo. Create a Python virtual environment and install the basics:

```bash
python -m venv .venv
source .venv/bin/activate   # use 'source .venv\Scripts\activate' on Windows
pip install openai pandas scikit-learn jupyter
```

Set your OpenAI key and run the notebook:

```bash
export OPENAI_API_KEY="your-openai-key"   # bash
jupyter notebook notebook.ipynb
```

## Extend this project

- Add a web UI for live chat
- Use a managed vector DB for production scale (Pinecone)
- Add a feedback loop to improve answers over time

## Contact

Questions? Create an issue or email: `uwintwali.umd@gmail.com`.

