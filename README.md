# 🚀 Enterprise AI Insights Dashboard (LLM + RAG)

An AI-powered enterprise dashboard that combines **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)** to deliver **grounded, explainable, and evidence-based insights** over enterprise data.

---

## 📄 Research Paper

👉 [Read Full Paper] https://zenodo.org/records/19412661

This research presents the design and implementation of an enterprise AI dashboard that augments traditional analytics with natural language reasoning and retrieval-based grounding.

---

## 🧠 Problem Statement

Traditional enterprise dashboards:
- Show **what happened** (metrics, charts)
- Do NOT explain **why it happened**
- Require users to manually explore multiple systems
- Lack **contextual insights and traceability**

LLMs enable natural language interaction, but:
- Can generate **hallucinated responses**
- Lack grounding in enterprise-specific data

---

## 💡 Solution

This project implements a **RAG-based AI dashboard** that:

- Retrieves relevant enterprise records
- Generates **context-aware responses**
- Provides **supporting evidence**
- Combines **analytics + reasoning + explainability**

---

## 🏗️ System Architecture

The system consists of:

1. **Data Layer**
   - Synthetic enterprise records (issues, logs, policies)

2. **Embedding Layer**
   - Converts text into vector representations

3. **Vector Search**
   - FAISS-based similarity search

4. **Retrieval Engine**
   - Top-k relevant document retrieval

5. **LLM Reasoning Layer**
   - Generates grounded responses

6. **Application Layer**
   - FastAPI backend

7. **Frontend Dashboard**
   - React-based UI with KPI cards and query interface

---

## 🔄 End-to-End Flow

1. User views dashboard KPIs  
2. User asks a question  
3. Backend retrieves relevant records  
4. Prompt is constructed with evidence  
5. LLM generates response  
6. UI displays:
   - Answer (left)
   - Evidence (right)

---

## 🚀 Features

- 📊 KPI-based dashboard (summary metrics)
- 💬 Natural language query interface
- 🔍 Semantic search using embeddings
- 📄 Evidence-backed responses
- 🧠 Explainable AI outputs
- ⚡ FastAPI backend for orchestration
- 🎨 React frontend for visualization

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- CSS

### Backend
- FastAPI
- Python

### AI / ML
- Sentence Transformers (embeddings)
- FAISS (vector database)
- LLM (currently mocked, extendable to OpenAI)

---
