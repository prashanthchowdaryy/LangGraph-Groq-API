# LangGraph + Groq API Example

This project shows how to build a simple AI workflow using LangGraph and Groq API.
It demonstrates how graph-based workflows can manage multi-step reasoning with LLMs.

---

## Features

* Graph-based AI workflow
* Uses LangGraph with LangChain
* Integrates Groq API
* Supports multi-step reasoning
* Simple and easy to understand

---

## Tech Stack

* Python
* LangGraph
* LangChain
* Groq API
* Jupyter Notebook

---

## Project Structure

* langgraph_groq_api.ipynb
* requirements.txt
* README.md

---

## How It Works

The workflow is built using three main concepts:

**State**
Stores shared data between steps
Example:
state = {
"question": "...",
"answer": ""
}

**Nodes**
Each node performs a task like processing input or generating a response

**Edges**
Control the flow between nodes

---

## Workflow

User Input → Process Query → Generate Response → Output

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/langgraph-groq-demo.git

Go to the folder:

cd langgraph-groq-demo

Install dependencies:

pip install -r requirements.txt

---

## Usage

Run the notebook:

jupyter notebook

Open:

langgraph_groq_api.ipynb

---

## Key Learning

* Graph-based AI workflows
* LangGraph basics
* Multi-step reasoning
* Using Groq API with LangChain
