# 🤖 WhatsApp AI Automation Agent (n8n)

**Enterprise-grade AI agent for WhatsApp** built with **n8n**, **OpenAI GPT**, and **RAG (Retrieval-Augmented Generation)**.  
This system automates business conversations, customer support, lead generation, and scheduling — all inside WhatsApp.

---

## 🧠 Core Features

### 🤖 AI Conversational Engine
- Natural language understanding (text + voice)
- Context-aware responses  
- Image & link support  

### 🔄 Workflow Automation
- Built with **n8n** visual workflow builder  
- API & Webhook integration  
- Multi-service orchestration  

### 📚 RAG Knowledge System
- Store documents in a vector database  
- Answer from PDFs & company docs  
- Embedding-based retrieval  

### 📅 Business Integrations
- Google Calendar scheduling  
- Email notifications  
- CRM & lead automation  

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Orchestration | n8n |
| AI | OpenAI GPT |
| RAG | Pinecone / FAISS |
| Messaging | WhatsApp API / Evolution API |
| Backend | Python |
| Deployment | Docker / Cloud |

---

## 🏗 Architecture

WhatsApp User
│
▼
WhatsApp Cloud API
│
▼
n8n Orchestrator
│
├── AI Agent (OpenAI)
├── RAG Pipeline
├── Calendar Agent
├── CRM & Leads
└── Notifications

---

## 🚀 Use Cases

- Customer support bot  
- Lead qualification  
- Appointment booking  
- Knowledge-base assistant  
- Multilingual WhatsApp agent  

---

## 📦 Getting Started

### Requirements
- Docker & Node.js  
- n8n (cloud or self-hosted)  
- WhatsApp API  
- OpenAI API key  
- Pinecone or FAISS  

### Setup
```bash
git clone https://github.com/AshrafRauf89/whatsapp-ai-agent-n8n.git
cd whatsapp-ai-agent-n8n
Import workflows into n8n:
Workflows → Import → JSON files

🧠 How It Works

User sends message on WhatsApp

Webhook triggers n8n

Message goes to AI agent

RAG retrieves best knowledge

Response sent back

📫 Contact

Ashraf Rauf
📧 ashrafrauf.icdl@yahoo.com

🔗 https://github.com/AshrafRauf89
