# PrivateGPT – Local AI Document Q&A System

A **secure, local, and privacy-friendly AI system** that lets you ask questions directly about your own documents — powered by **PrivateGPT** and local Large Language Models (LLMs).  
All data processing happens **100% offline** — ensuring complete privacy and control over your data.

---

## 🚀 Features
- ✅ Ask questions about local PDFs, DOCX, CSV, or TXT files  
- ✅ Works fully offline — no API or internet required  
- ✅ Uses embeddings and vector databases for accurate retrieval  
- ✅ Supports multiple LLM backends (GPT4All, Llama, Mistral, etc.)  
- ✅ Privacy-first: your documents never leave your machine  

---

<img width="1536" height="962" alt="PrivateGPT Sc simple" src="https://github.com/user-attachments/assets/fb6d89dd-9908-4f3a-b551-1ac75e5fd6d3" />

---

## 🧩 Tech Stack
- **Python 3.10+**
- **LangChain**
- **ChromaDB / FAISS**
- **SentenceTransformers / OpenAI Embeddings**
- **GPT4All / LlamaCpp**
- **Streamlit / FastAPI** (optional web interface)

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MohamadAub/privategpt-local-ai-qa.git
cd privategpt-local-ai-qa
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run PrivateGPT
```bash
python private_gpt.py
```

---

## 📂 Folder Structure
```
📁 privategpt-local-ai-qa
│
├── data/                 # Folder for local documents
├── embeddings/           # Vectorized document data
├── models/               # LLM model storage
├── private_gpt.py        # Main application
├── requirements.txt      # Dependencies
└── README.md             # Documentation
```

---

## 🧠 Example Queries
> “Summarize this document.”  
> “What are the key points in the uploaded paper?”  
> “Which section mentions financial data?”

---

## 🔒 Privacy First
Your data **never leaves your computer**.  
All processing — from embedding to AI responses — happens locally.

---

## 🪪 License
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author
**Mohamad Aub**  
🌐 [GitHub Profile](https://github.com/MohamadAub)  
📧 *mmelayoubii@gmail.com*
