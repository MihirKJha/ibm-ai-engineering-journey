# 📄 PDF Question Answering Chatbot (RAG) with IBM watsonx.ai

A Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask natural language questions about their contents. The application leverages **LangChain**, **IBM watsonx.ai**, **ChromaDB**, and **Gradio** to build an intelligent document question-answering system.

---

## 📌 Project Overview

Searching through lengthy PDF documents manually can be time-consuming. This project solves that problem by combining document retrieval with Large Language Models (LLMs).

The application:

- Uploads PDF documents
- Extracts and splits document text
- Generates vector embeddings
- Stores embeddings in ChromaDB
- Retrieves relevant document chunks
- Uses IBM Granite LLM to generate context-aware answers
- Provides an interactive Gradio web interface

---

## 🚀 Features

- Upload PDF documents
- Intelligent Question Answering
- Retrieval-Augmented Generation (RAG)
- IBM Granite LLM integration
- Chroma Vector Database
- LangChain RetrievalQA pipeline
- Watsonx Embeddings
- Interactive Gradio UI
- Automatic document chunking
- Semantic similarity search

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python 3.11 |
| Frontend | Gradio |
| LLM | IBM Granite |
| AI Platform | IBM watsonx.ai |
| Framework | LangChain |
| Embeddings | Watsonx Embeddings |
| Vector Database | ChromaDB |
| Document Loader | PyPDFLoader |
| PDF Parser | PyPDF |

---

## 📂 Project Structure

```text
.
├── qabot.py
├── requirements.txt
├── README.md
└── sample_pdfs/
```

---

## 🏗 Architecture

```text
                 User
                   │
                   ▼
          Upload PDF Document
                   │
                   ▼
             PyPDFLoader
                   │
                   ▼
     RecursiveCharacterTextSplitter
                   │
                   ▼
        Watsonx Embedding Model
                   │
                   ▼
             Chroma Vector DB
                   │
                   ▼
             Retriever
                   │
                   ▼
        RetrievalQA (LangChain)
                   │
                   ▼
        IBM Granite Foundation Model
                   │
                   ▼
           AI Generated Answer
                   │
                   ▼
             Gradio Interface
```

---

## 🔄 Application Workflow

1. Upload a PDF document.
2. Load the document using PyPDFLoader.
3. Split the document into manageable chunks.
4. Generate vector embeddings using IBM Watsonx Embeddings.
5. Store embeddings in ChromaDB.
6. Retrieve relevant chunks based on the user's query.
7. Send the retrieved context to IBM Granite LLM.
8. Return the generated answer through the Gradio interface.

---

## ⚙ Installation

### Clone the Repository

```bash
git clone 'repo-url'

cd genai_gradio_qabot_app
```

### Create a Virtual Environment

**Linux / macOS**

```bash
python -m venv my_env
source my_env/bin/activate
```

**Windows**

```bash
python -m venv my_env
my_env\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶ Running the Application

```bash
python qabot.py
```

Open your browser:

```
http://127.0.0.1:7860
```

---

## 💬 Example

### User Query

```text
Summarize the uploaded document.
```

### Response

```text
The uploaded document discusses...
```

---

## 📚 Key Components

- **PyPDFLoader** – Loads PDF documents
- **RecursiveCharacterTextSplitter** – Splits text into chunks
- **Watsonx Embeddings** – Converts text into vector embeddings
- **ChromaDB** – Stores document embeddings
- **Retriever** – Finds relevant document chunks
- **RetrievalQA** – Combines retrieval with LLM inference
- **IBM Granite** – Generates final answers
- **Gradio** – Provides a web interface

---

## 🎯 Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- LangChain Pipelines
- Vector Databases
- Semantic Search
- Document Processing
- Prompt Engineering
- Large Language Models
- IBM watsonx.ai
- ChromaDB
- Python Development

---

## 🔮 Future Enhancements

- Multi-PDF support
- Persistent vector database
- Conversation memory
- Streaming responses
- Citation generation
- Hybrid search (BM25 + Vector Search)
- OCR support for scanned PDFs
- Docker deployment
- Cloud deployment
- Authentication

---

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Mihir Jha**

AI • Backend • Cloud Engineering

Building production-ready AI systems using LLMs, RAG, Agentic AI, Cloud, and Microservices.