---
title: Company Policies Chatbot
emoji: 🏢
colorFrom: blue
colorTo: purple
sdk: gradio
sdk_version: 4.0.0
app_file: app.py
pinned: false
---

# Company Policies Chatbot

A RAG-based chatbot that answers questions about company policies using Groq, HuggingFace embeddings, and FAISS vector store.

## Features

- 📁 Upload multiple PDF policy documents
- 🔍 Semantic search using FAISS
- 💬 Natural language Q&A with Groq LLM
- 📚 Source citations for answers

## How to Use

1. Upload your company policy PDFs
2. Click "Process Documents"
3. Ask questions about the policies
4. Get detailed answers with source references

## Tech Stack

- **LLM**: Groq (Llama 3.1)
- **Embeddings**: HuggingFace Sentence Transformers
- **Vector Store**: FAISS
- **Framework**: Gradio