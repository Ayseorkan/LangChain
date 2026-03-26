# LLM Applications with LangChain 🚀

> 🚀 This repository showcases implementations of modern LLM systems for practical AI solutions.

---

## 📌 Overview

This repository contains hands-on implementations of Large Language Model (LLM) applications using LangChain and OpenAI.

It focuses on building real-world AI systems such as Retrieval-Augmented Generation (RAG), prompt pipelines, and intelligent agents.

---

## 🧠 Key Concepts

### 🔹 Prompt Engineering
Designing effective prompts to improve LLM outputs.

### 🔹 Chains
Combining prompts, models, and output parsers into structured pipelines.

### 🔹 Retrieval-Augmented Generation (RAG)
Enhancing LLM responses using external knowledge sources like websites and documents.

### 🔹 Agents & Tools
Building systems that can interact with external tools such as search APIs and vector databases.

---

## 📂 Project Structure

```text
llm-apps-with-langchain/
├── fundamentals/
│   ├── llm_basics.ipynb
│   ├── prompt_engineering_basics.ipynb
│   └── chains.ipynb
├── rag/
│   ├── retrieval_augmented_generation.ipynb
│   └── rag_chat_with_website.ipynb
├── tools/
│   └── rag_with_tools.ipynb
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt 

---

## ⚙️ Installation

git clone https://github.com/yourusername/llm-apps-with-langchain.git
cd llm-apps-with-langchain
pip install -r requirements.txt

---

## 🔑 Environment Variables

Create a .env file in the root directory:

OPENAI_API_KEY=your_api_key_here
TAVILY_API_KEY=your_api_key_here 

---

## 🚀 Example Use Cases

- Ask questions over a website using RAG
- Build context-aware chat systems
- Generate structured outputs from prompts
- Integrate LLMs with external tools

---

## 🛠️ Technologies Used

- LangChain
- OpenAI API
- FAISS / Chroma (Vector Databases)
- Python

---

## 🎯 Goal

The goal of this repository is to go beyond basic tutorials and demonstrate how to build real AI-powered applications using modern LLM frameworks.