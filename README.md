# Food RAG Chatbot

A food recommendation system built with Python, ChromaDB and IBM watsonx Granite. It includes semantic search, metadata filtering and a RAG chatbot.

## Setup (run this first)

Install the dependencies before running anything:

```bash
pip install torch --index-url https://download.pytorch.org/whl/cpu
pip install -r requirements.txt
```

Note: torch is installed separately because it uses the CPU-only download link.

## Run

```bash
python3.11 interactive_search.py
```
