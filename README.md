# n8n-rag-chatbot
An n8n-powered Retrieval-Augmented Generation chatbot that ingests documents, stores embeddings in Pinecone, and answers user queries using OpenAI models with memory support.
# 🤖 n8n RAG Chatbot Automation

A **Retrieval-Augmented Generation (RAG)** chatbot automation built using **n8n**, **OpenAI**, and **Pinecone**.  
This workflow allows users to ingest documents, store embeddings in a vector database, and answer questions contextually using an AI agent with memory.

---

## 🚀 Features

- 📄 Document ingestion via form submission
- 🧠 Vector embeddings using OpenAI
- 🗂 Storage and retrieval with Pinecone
- 💬 Chat-based question answering
- 🧩 AI Agent with conversational memory
- ⚡ Fully no-code / low-code automation using n8n

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **OpenAI** – Embeddings & chat models
- **Pinecone** – Vector database
- **RAG Architecture** – Retrieval + Generation

---

## 🧩 Workflow Overview

The automation consists of:

1. **Form Trigger** – Accepts documents for ingestion  
2. **OpenAI Embeddings** – Converts text into vectors  
3. **Pinecone Vector Store** – Stores document embeddings  
4. **Chat Trigger** – Receives user queries  
5. **AI Agent** – Retrieves relevant context and generates responses  
6. **Memory Node** – Maintains conversation history  

---

## 📂 Repository Structure

