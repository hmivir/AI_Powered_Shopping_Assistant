# 🛒 AI-Powered Shopping Assistant

Conversational shopping assistant powered by LLMs, featuring semantic product search, cart management, and automatic escalation to human support. Built as a realistic e-commerce use case using modern NLP, embeddings, vector databases, and agent orchestration.

---

## 🚀 Project Overview

This project simulates the implementation of a **virtual shopping assistant** that can:

- Search for products by name or need (e.g., "healthy snacks")
- Add/remove items from the shopping cart
- Handle customer queries, refunds, and complaints
- Escalate complex situations to human support

The system combines structured and semantic search using advanced **natural language processing (NLP)** techniques, enabling hybrid queries by filters or meaning.

---

## 🧠 Motivation

This project was developed as the final assignment for the specialization **"Building Next-Gen AI Solutions with Agents"** at Anyone AI.

**Business Case**: A major e-commerce company seeks to **enhance customer experience** and **automate support services** through intelligent conversational agents and generative AI.

---

## ⚙️ Technologies Used

| Area                    | Tools & Frameworks                          |
|-------------------------|---------------------------------------------|
| LLMs                    | Gemini 1.5 Pro (GCP), LangChain             |
| Agent Orchestration     | LangGraph                                   |
| Embeddings              | HuggingFace, ChromaDB                       |
| Backend & Data Handling | Python, Pydantic, Pandas                    |
| Frontend UI             | Streamlit                                   |
| Testing                 | Pytest                                      |
| Code Style              | Black (PEP-8 formatting)                    |

<pre markdown="1"> ``` ## 📁 Project Structure 
    ├── src/ # Core logic (tools, agents, prompts, graph, state)
    ├── tests/ # Unit and integration tests
    ├── dataset/ # Product catalog and historical order data
    ├── app.py # Streamlit web interface
    ├── download_dataset.py # Script to download and extract dataset
    ├── requirements.txt # Python dependencies
    └── README.md # This file ``` </pre>

## 🔧 Installation

### Prerequisites

- Python 3.10+
- Google Cloud API Key (for Gemini)
- Git (optional)

### Install dependencies

```bash
pip install -r requirements.txt

```
### Set your API Key (Google, OpenAI, etc.)

```bash
    export GOOGLE_API_KEY="your-api-key-here"
```

### First, build the Vector Data Base

Download the dataset before starting:

```python
download_dataset.py
```
The vector DB enables semantic product search using text embeddings.

```bash
    python src/build_vector_db.py
```

Maximiliano Ivir
Machine Learning Engineer | Data Scientist  | PhD in Biochemistry
🔗 [LinkedIn](https://www.linkedin.com/in/hmivir/)
💻 [GitHub](https://github.com/hmivir)
