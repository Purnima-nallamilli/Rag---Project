# 📄 RAG-Based PDF Question Answering System

## 🔍 Overview

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that enables users to ask natural language questions from policy documents. The system processes PDF files, retrieves relevant content using vector search, and generates accurate answers using a Large Language Model.

---

## 🎯 Objective

To build an intelligent document assistant capable of retrieving and generating context-aware answers from enterprise policy PDFs such as Terms & Conditions documents.

---

## 🚀 Features

* 📥 PDF ingestion and text extraction
* ✂️ Document chunking & preprocessing
* 🔎 Semantic search using embeddings
* 🗄️ Chroma vector database storage
* 🤖 Gemini LLM answer generation
* 📑 Source-aware response retrieval

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **HuggingFace Embeddings**
* **ChromaDB (Vector Database)**
* **Google Gemini LLM**
* **PyPDF Loader**

---

## 🏗️ System Architecture

User Query → Retriever → Vector DB → Relevant Chunks → Gemini LLM → Final Answer

---

## 📂 Dataset

* MakeMyTrip Homestay Awards Terms & Conditions PDF
* Policy and eligibility rule-based document

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run Application

```bash
python app.py
```

---

## 💡 Sample Queries

* Am I eligible to apply for the Homestay Awards?
* What are the luxury homestay eligibility criteria?
* How are winners selected?
* Can previous winners apply again?

---

## 📊 Use Cases

* Policy document assistant
* Legal document QA system
* HR handbook chatbot
* Enterprise knowledge retrieval

---

## 🔮 Future Enhancements

* Streamlit chatbot UI
* Multi-PDF knowledge base
* Source citation highlighting
* Cloud deployment

---

## ⭐ Project Highlights

* Built end-to-end RAG pipeline
* Integrated embeddings + vector DB + LLM
* Demonstrates real-world GenAI application
