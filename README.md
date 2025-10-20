# 🧠 Smart PDF Data Extractor  
*AI-powered document intelligence system built with LangChain, OpenAI, and ChromaDB.*

---

## 🏗️ Overview

**Smart PDF Data Extractor** is an AI-powered application that intelligently reads PDF documents (like research papers, reports, or forms) and extracts structured information such as:

- 📄 **Title**  
- ✍️ **Authors**  
- 🧾 **Summary**  
- 📅 **Publication Year**  

This project uses **Large Language Models (LLMs)** via **LangChain**, vector storage with **ChromaDB**, and a user-friendly **Streamlit** interface to build a complete end-to-end **Document Understanding Pipeline**.

> ⚡ Goal: Transform unstructured PDF data into meaningful, machine-readable insights.

---

## 🚀 Key Features

✅ **Automated PDF Data Extraction** — Reads and analyzes any research paper or report.  
✅ **AI-Powered Insights** — Uses OpenAI GPT models for accurate, contextual extraction.  
✅ **Structured Output** — Extracts clean JSON-like data with titles, summaries, authors, etc.  
✅ **Vector Database Integration** — Stores and retrieves document embeddings using ChromaDB.  
✅ **Interactive Streamlit App** — Upload, visualize, and query results instantly.  
✅ **Modular & Extensible** — Easily adaptable for invoices, resumes, or legal document parsing.

---

## 🧠 Tech Stack

| Tool | Purpose |
|------|----------|
| **Python** | Core development language |
| **LangChain** | Orchestrates LLM workflows |
| **OpenAI GPT-4o-mini** | Performs extraction and summarization |
| **ChromaDB** | Stores embeddings for semantic retrieval |
| **PyPDF / LangChain DocumentLoaders** | PDF parsing |
| **Streamlit** | Frontend web UI |
| **Pandas / JSON** | Structured data representation |

---

## 🪄 How It Works

1. **Upload a PDF** → The app reads and splits text into small chunks.  
2. **Generate Embeddings** → Each chunk is converted into a numerical vector using OpenAI embeddings.  
3. **Store in ChromaDB** → Vectors are indexed locally for retrieval.  
4. **Query via LLM** → The model retrieves the most relevant chunks and extracts structured fields.  
5. **Display Results** → Streamlit interface shows neatly formatted JSON or table view.

---

