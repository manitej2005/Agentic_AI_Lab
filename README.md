# LLM Lab Assignment using Ollama

This repository contains the implementation of four LLM-based applications using the Ollama framework and the Qwen2.5:3B model running locally.

## Technologies Used

- Python
- Ollama
- Qwen2.5:3B
- LangChain
- ChromaDB
- Sentence Transformers
- PyPDF

---

## Project Structure

```
LLM-Lab-Assignment/
│
├── llm_workflow.py
├── prompt_chaining.py
├── agentic_ai.py
├── rag_qa.py
│
├── knowledge.pdf
├── requirements.txt
├── README.md
└── chroma_db/
```

---

## Installation

Clone the repository

```
git clone <repository-url>
```

Create virtual environment

```
python -m venv venv
```

Activate virtual environment

Windows

```
venv\Scripts\activate
```

Install dependencies

```
pip install -r requirements.txt
```

Run Ollama

```
ollama serve
```

Ensure the model exists

```
ollama list
```

If not installed

```
ollama pull qwen2.5:3b
```

---

## Programs

### 1. llm_workflow.py

Basic interaction with the LLM.

---

### 2. prompt_chaining.py

Generates

- Summary
- Key Points
- Interview Questions

---

### 3. agentic_ai.py

Implements

- Planning
- Execution
- Final Response

---

### 4. rag_qa.py

Loads a PDF

Creates embeddings

Stores vectors

Answers questions using Retrieval Augmented Generation.

---

## Model Used

Qwen2.5:3B

Running locally using Ollama.
