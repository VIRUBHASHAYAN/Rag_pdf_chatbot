# RAG PDF Question Answering System

This project implements a Retrieval-Augmented Generation (RAG) system
that answers user questions based on a PDF document.

## Features
- PDF document loading
- Text chunking
- Embedding generation
- Vector similarity search
- LLM-based answer generation

## Tech Stack
- Python
- LangChain
- HuggingFace Embeddings
- Vector Store
- Groq api

## How It Works
1. Load PDF
2. Split into chunks
3. Convert chunks into embeddings
4. Store in vector database
5. Retrieve relevant chunks
6. Generate final answer using LLM
