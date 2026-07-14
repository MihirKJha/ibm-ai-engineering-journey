# 🤖 IBM watsonx.ai Chatbot with Gradio

An interactive AI chatbot built using **Gradio**, **IBM watsonx.ai**, and **LangChain**. This project demonstrates how to build a simple yet production-style web interface that enables users to communicate with Large Language Models (LLMs) such as **Meta Llama** and **Mistral** through IBM watsonx.ai.

The project showcases how modern AI applications combine an intuitive frontend with powerful foundation models to deliver real-time question-answering experiences.

---

## 📌 Project Overview

Large Language Models are powerful, but they require an interface that allows users to interact with them easily.

This project uses **Gradio** to create a lightweight web application where users can enter questions and receive AI-generated responses from IBM watsonx.ai models.

The chatbot demonstrates the complete workflow of:

- Creating an interactive web interface
- Connecting to IBM watsonx.ai
- Using LangChain as the LLM wrapper
- Sending prompts to a foundation model
- Displaying generated responses in real time

---

## 🚀 Features

- Interactive web-based chatbot
- IBM watsonx.ai integration
- Supports Meta Llama and Mistral foundation models
- LangChain-powered LLM interface
- Simple and clean Gradio UI
- Easy model switching
- Beginner-friendly architecture
- Local deployment

---

## 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python 3.11 |
| Frontend | Gradio |
| AI Platform | IBM watsonx.ai |
| LLM Framework | LangChain |
| Models | Meta Llama, Mistral |
| Backend | WatsonxLLM |
| Web Server | FastAPI, Uvicorn |

---

## 📂 Project Structure

```text
.
├── llm_chat.py
├── simple_llm.py
├── gradio_demo.py
├── common_input_types.py
├── requirements.txt
└── README.md
```

---

## 🏗 Architecture

```text
                 User
                   │
                   ▼
        Gradio Web Interface
                   │
                   ▼
          generate_response()
                   │
                   ▼
          LangChain WatsonxLLM
                   │
                   ▼
           IBM watsonx.ai API
                   │
                   ▼
      Meta Llama / Mistral Model
                   │
                   ▼
        AI Generated Response
                   │
                   ▼
             Gradio Output
```

---

## ⚙ Installation

### 1. Clone the Repository

```bash
git clone 'repo-url'

cd 'folder_name'
```

### 2. Create a Virtual Environment

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

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ⚙ Configuration

Select the foundation model you want to use.

### Meta Llama

```python
model_id = "meta-llama/llama-3-2-11b-vision-instruct"
```

### Mistral

```python
model_id = "mistralai/mistral-small-3-1-24b-instruct-2503"
```

Configure generation parameters:

```python
parameters = {
    GenParams.MAX_NEW_TOKENS: 256,
    GenParams.TEMPERATURE: 0.5
}
```

---

## ▶ Running the Application

Launch the Gradio chatbot:

```bash
python llm_chat.py
```

Open your browser and navigate to:

```
http://127.0.0.1:7860
```

---

## 💬 Example

### User Input

```text
How can I become a better Data Scientist?
```

### Chatbot Response

```text
To become a successful Data Scientist, focus on building strong
foundations in mathematics, statistics, programming,
machine learning, and communication skills...
```

---

## 📚 Learning Objectives

This project demonstrates:

- Building AI web applications with Gradio
- Integrating IBM watsonx.ai foundation models
- Using LangChain with external LLMs
- Prompting Large Language Models (LLMs)
- Creating interactive chatbot interfaces
- Deploying local AI applications

---

## 🎯 Skills Demonstrated

- Python Development
- Prompt Engineering
- Large Language Models (LLMs)
- IBM watsonx.ai
- LangChain
- Gradio
- AI Application Development
- API Integration
- Foundation Models

---

## 🔮 Future Enhancements

- Multi-turn conversation memory
- Streaming AI responses
- Retrieval-Augmented Generation (RAG)
- PDF and document chat
- Chat history
- User authentication
- Docker deployment
- Cloud deployment
- Model selection from UI
- REST API integration

---

## 📖 References

- IBM watsonx.ai
- LangChain
- Gradio

---

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Mihir Jha**

AI • Backend • Cloud Engineering

Building production-ready AI systems using LLMs, RAG, Agentic AI, Cloud, and Microservices.