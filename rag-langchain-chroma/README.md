# 🧠 RAG Pipeline using LangChain + ChromaDB

This notebook demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using only free and open-source tools:

- ✅ `LangChain` for modular chains
- ✅ `ChromaDB` as the vector store
- ✅ `SentenceTransformers` for embeddings

---

## 📌 What This Covers
| Step | Description |
|------|-------------|
| 1. | Create semantic embeddings using `all-MiniLM-L6-v2` |
| 2. | Store and persist them using `ChromaDB` |
| 3. | Perform similarity search on query |
| 4. | Build a RAG-style retriever pipeline with `LangChain` |
| 5. | (Optional) Use a mock LLM or replace with your own local model |

---

## 🧪 Requirements
```bash
pip install langchain chromadb sentence-transformers tiktoken
```

---

## 🚀 How to Run
1. Open the notebook in Google Colab or locally
2. Step through the cells
3. Edit `doc_texts` to simulate your own document chunks
4. Replace the `FakeListLLM` with a real model (e.g., HuggingFace Pipeline or OpenRouter LLM)

---

## 💡 Why LangChain + Chroma?
- Easy-to-use Python API for chaining retrieval + generation
- Chroma is ultra-lightweight and runs on CPU
- Perfect for local search, knowledge base QnA, or offline chatbots

---

## 🌱 Real-World Use Cases
- Build **RAG assistants** over your docs
- Academic QnA from PDFs
- Internal enterprise search (private + local)
- Resume / portfolio LLM search tools

---

## 🧠 Part of `llm-learning-hub`
This notebook is part of a complete AI engineer portfolio series built around free GenAI tools.

---

## ✨ Author
**Muhammad Taha Nasir** — AI Engineer in Training · Building smart, open-source AI apps  
> 🔗 Follow: [linkedin.com/in/muhammadtahanasir](https://linkedin.com/in/muhammadtahanasir)

---

**Ready to build local RAG apps? Run this notebook.**
