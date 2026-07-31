# 📚 Educational RAG Chatbot

## Overview

This project implements a Retrieval-Augmented Generation (RAG) chatbot using Python and Google Colab.

The chatbot extracts text from educational PDF documents, converts them into vector embeddings using Sentence Transformers, stores them in FAISS, retrieves the most relevant information for a user's question, and generates answers using the Google Gemini API.

---

## Features

- Upload educational PDFs
- Extract text using PyPDF
- Split text into chunks
- Generate embeddings using all-MiniLM-L6-v2
- Store embeddings in FAISS
- Retrieve Top-5 relevant chunks
- Generate answers using Google Gemini
- Simple and easy to understand implementation

---

## Tech Stack

- Python
- Google Colab
- PyPDF
- Sentence Transformers
- FAISS
- Google Gemini API

---

## Project Structure

```
Educational-RAG-Chatbot
│
├── Educational_RAG.ipynb
├── app.py
├── README.md
├── requirements.txt
├── data/
│   └── OPERATING-SYSTEMS.pdf
└── vector_db/
```

---

## Workflow

1. Upload PDF
2. Extract Text
3. Create Chunks
4. Generate Embeddings
5. Store in FAISS
6. Retrieve Relevant Chunks
7. Generate Answer using Gemini API

---

## Sample Questions

- What is CPU Scheduling?
- Explain Deadlock.
- What is Paging?
- Explain Process Synchronization.

---

## Future Improvements

- Multiple PDF Support
- Streamlit Web Interface
- Chat History
- ChromaDB
- Citations with Page Numbers

---

## Author

**Poorvika N**# Educational-RAG-Chatbot
