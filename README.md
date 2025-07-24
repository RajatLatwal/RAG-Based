# 📄 RAG-Based PDF Question Answering System

A lightweight and efficient **RAG (Retrieval-Augmented Generation)** system built using:
- 🤗 HuggingFace Embeddings
- 🧠 FAISS for vector storage
- 🌐 Google Gemini Pro (via Generative AI API)
- 🎈 Streamlit for an interactive UI

---

## 🚀 Features

- 📤 Upload any PDF document
- 🧩 Text is chunked and embedded using HuggingFace
- 🔍 FAISS retrieves the most relevant chunks
- 🤖 Gemini Pro generates intelligent answers
- 🔄 Auto-clear query input after each submission

---

## 🌐 Live Demo

👉 [Click here to try it now!](https://rag-based-system-genai.streamlit.app/)  
_**No setup required — just upload a PDF and start chatting!**_

---

## 🧱 Tech Stack

| Tool/Library         | Purpose                          |
|----------------------|----------------------------------|
| `Streamlit`          | UI / Frontend                    |
| `FAISS`              | Memory Vector Database           |
| `HuggingFace`        | Embedding Model (MiniLM-L6-v2)   |
| `Google Generative AI (Gemini)` | Answer Generation     |
| `LangChain`          | Text Splitting / Schema Wrapper  |
| `PyPDF`              | PDF Text Extraction              |

---
