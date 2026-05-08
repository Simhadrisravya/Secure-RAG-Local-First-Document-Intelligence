
# 🚀 Secure-RAG: Local-First Document Intelligence

A lightweight, privacy-focused **Retrieval-Augmented Generation (RAG)** pipeline. This project demonstrates how to ground Large Language Models (LLMs) in custom data while keeping the embedding and retrieval process entirely local for maximum security and zero cost.



## 🌟 Key Features
- **Privacy-First:** Document embeddings are generated locally; your data stays on your machine.
- **Hybrid Efficiency:** Uses **FAISS** (Facebook AI Similarity Search) for lightning-fast context retrieval.
- **Hallucination Mitigation:** By providing specific context, the LLM is forced to answer based on facts, not training data.
- **Cost-Optimized:** Uses open-source `sentence-transformers` for embeddings instead of paid APIs.

## 🛠️ Tech Stack
- **Framework:** LangChain
- **Vector Store:** FAISS
- **Embeddings:** HuggingFace (`all-MiniLM-L6-v2`)
- **LLM:** OpenAI GPT-4o-mini

## 📂 Project Structure
```text
├── data/               # Your source text files (e.g., info.txt)
├── main.py             # Main RAG logic
├── requirements.txt    # Project dependencies
└── .env.example        # Environment variable template


<img width="1487" height="358" alt="rag demo_png" src="https://github.com/user-attachments/assets/b9ab58cf-6d17-4e66-83be-f1ac68633042" />
