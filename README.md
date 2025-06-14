# 🧠 Multi-Document Question Answering using RAG

A powerful **Retrieval-Augmented Generation (RAG)** pipeline that enables **question answering over multiple documents** (PDFs, text files, etc.). Built with **LangChain**, **HuggingFace embeddings**, **ChromaDB**, and **Groq’s ultra-fast LLMs**.

---

## 🚀 Demo Overview

✅ Load and chunk multiple PDF/text documents  
✅ Embed chunks using HuggingFace models  
✅ Store in ChromaDB (vector DB)  
✅ Answer questions with Groq’s LLM using retrieved context  

---

## 📦 Tech Stack

| Layer         | Tool / API                 |
|---------------|----------------------------|
| Embeddings    | `HuggingFace Transformers` |
| Vector DB     | `Chroma`                   |
| RAG Engine    | `LangChain`                |
| LLM Inference | `Groq`                     |
| Parsing       | `unstructured`, `PyPDF2`   |

---

## 🛠 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/multi-doc-qa-rag.git
cd multi-doc-qa-rag
