<p align="center">
  <img src="https://dummyimage.com/1200x250/0d1117/ffffff&text=PDF+RAG+Chatbot+%7C+AI-Powered+PDF+Question+Answering" alt="PDF RAG Chatbot Banner">
</p>

# 📘 DocuMind AI: Retrieval‑Augmented PDF Question Answering System

A fully featured **Retrieval-Augmented Generation (RAG)** application that reads PDF documents and answers user questions using **LangChain**, **ChromaDB**, and **Gradio**.  

This project is designed as a **portfolio-quality AI engineering project**.

---

## 🚀 Overview

This application allows users to upload a PDF and interact with it through natural language. It:

- Extracts text from PDFs  
- Splits text into manageable chunks  
- Converts chunks into embeddings  
- Stores them in a vector database  
- Retrieves relevant context  
- Generates answers using an LLM  
- Exposes everything through a clean Gradio web interface  

---

## 🧠 Tech Stack

- **Language Model:** LangChain LLM  
- **Vector Database:** ChromaDB  
- **Embeddings:** Sentence Transformers / LangChain Embeddings  
- **Interface:** Gradio  
- **Document Loader:** PyPDFLoader  

---

## 🏗️ How It Works

1. **PDF Upload** – The user uploads a PDF through the Gradio UI.  
2. **Text Extraction & Splitting** – The PDF text is extracted and split into smaller chunks.  
3. **Embedding Generation** – Each chunk is converted into a vector representation.  
4. **Vector Storage** – Embeddings are stored in **ChromaDB**.  
5. **Retrieval** – When a question is asked, the most relevant chunks are retrieved.  
6. **Answer Generation** – The QA chain uses the retrieved context to generate an answer.

---

## 🖥️ Features

- 📄 PDF uploading  
- ✂️ Automatic text chunking  
- 🔍 Vector similarity search  
- 🤖 LLM-powered question answering  
- 🌐 Gradio web interface  
- ⚡ Lightweight, fast RAG pipeline  

---

## 📂 Project Structure

```text
📁 pdf-rag-chatbot
 ├── app.py
 ├── README.md
 └── requirements.txt  (optional)
