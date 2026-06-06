# 📄 RAG Document QA System – AI-Powered Document Chat

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Framework-orange?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval--Augmented--Generation-red?style=for-the-badge)

**Upload any document — PDF, DOCX, or TXT — and chat with it using AI.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [How It Works](#-how-it-works) • [Installation](#-installation)

</div>

---

## 🚀 What is RAG Document QA System?

RAG Document QA System is an **AI-powered Retrieval-Augmented Generation** application that lets users upload their own documents and ask questions in natural language. The system retrieves the most relevant sections from the document and generates accurate, context-aware answers — with **conversational memory** to handle follow-up questions intelligently.

> 💡 *Upload your document → Ask anything → Get instant AI-powered answers*

---

## ✨ Features

- 📂 **Multi-format Support** – Upload PDF, DOCX, and TXT files
- 🤖 **AI-Powered Q&A** – Get accurate answers from your document content
- 🧠 **Conversational Memory** – Remembers previous questions for follow-up context
- ⚡ **Real-time Responses** – Fast semantic search with vector embeddings
- 🔍 **Semantic Retrieval** – Finds most relevant document chunks intelligently
- 💬 **Multi-turn Chat** – Have a full conversation about your document
- 📊 **Large Document Support** – Handles long documents via smart text chunking

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core language |
| **LangChain** | RAG pipeline & LLM orchestration |
| **HuggingFace** | Embeddings & transformer models |
| **FAISS / ChromaDB** | Vector store for semantic search |
| **PyPDF2 / python-docx** | Document parsing |
| **Streamlit** | Web UI interface |

---

## ⚙️ How It Works
User uploads document (PDF / DOCX / TXT)
↓
Document parsed & split into chunks
↓
Chunks converted to vector embeddings (HuggingFace)
↓
Embeddings stored in vector database (FAISS)
↓
User asks a question
↓
Relevant chunks retrieved via semantic search
↓
LLM generates answer using retrieved context + chat memory
↓
Answer displayed to user in real-time

---

## 📁 Project Structure
RAG-Document-QA-System/
│
├── snetcha_docu_ai.zip     # Main project files
└── README.md

---

## 🔧 Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/amitkuma-1234/RAG-Document-QA-System.git
   cd RAG-Document-QA-System
```

2. **Extract the zip:**
```bash
   unzip snetcha_docu_ai.zip
```

3. **Install dependencies:**
```bash
   pip install langchain huggingface-hub faiss-cpu pypdf2 python-docx streamlit
```

4. **Run the app:**
```bash
   streamlit run app.py
```

---

## 💬 Example Usage
📂 Upload: research_paper.pdf
You: What is this document about?
AI: This document is about deep learning techniques for NLP...
You: What methods are used in the paper?
AI: The paper primarily uses transformer-based architectures...
You: Summarize the conclusion.
AI: In conclusion, the authors found that...

---

## 📌 Use Cases

- 📚 Chat with research papers & textbooks
- ⚖️ Query legal documents & contracts
- 🏥 Analyze medical reports & records
- 💼 Extract insights from business reports
- 🎓 Study from notes and academic PDFs

---

## 🙋‍♂️ Author

<div align="center">

**Amit Kumar**

[![GitHub](https://img.shields.io/badge/GitHub-amitkuma--1234-black?style=for-the-badge&logo=github)](https://github.com/amitkuma-1234)

⭐ **If you find this useful, please give it a star!** ⭐

</div>

---

<div align="center">
Made with ❤️ using LangChain + HuggingFace
</div>
