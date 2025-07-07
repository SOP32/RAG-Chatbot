# 🧠 RAG-Chatbot: Retrieval-Augmented Generation with LangChain & OpenAI

This project implements a chatbot that answers questions based on the content of uploaded PDF documents using Retrieval-Augmented Generation (RAG). It uses:

- 🧠 OpenAI GPT-4o (via LangChain)
- 📄 PDF loading & chunking
- 🔍 ChromaDB vector store
- 🧮 OpenAI Embeddings (`text-embedding-3-large`)
- 💬 Gradio for UI

---

## 🚀 Features

- Upload PDFs and convert them into searchable chunks
- Ask natural language questions about the document
- Answers are generated using only the document content
- Real-time chat interface using Gradio

---

## 📁 Project Structure

```bash
.
├── chatbot.py               # Main chatbot Gradio interface
├── ingest_database.py       # PDF loader, splitter, and vector store creator
├── data/                    # Directory to store your PDFs
├── chroma_db/               # ChromaDB persistent vector storage
├── .env                     # Your API key (not committed)
├── .gitignore               # Ignore large files and keys
