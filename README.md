# LangGraph Basics

A collection of basic examples and Jupyter Notebooks exploring workflows using **LangGraph**, **LangChain**, and local LLMs via **Ollama**.

## 📂 Contents
- `llm_workflow.ipynb`: A simple LangGraph implementation running a Question & Answer state machine loop.
- `linear_workflow.ipynb`: Exploring how to build and execute linear step-by-step node workflows.
- `sup.ipynb`: Additional experiments and LangGraph components.

## 🚀 Setup & Installation

1. **Install Python Dependencies:**
   It is recommended to run this inside a virtual environment (`myenv`).
   ```bash
   pip install langchain-ollama langgraph jupyter
   ```

2. **Setup Ollama (Local LLM):**
   Make sure you have [Ollama](https://ollama.com/) installed and running on your machine.
   You will need to pull your desired models before running the notebooks:
   ```bash
   ollama pull llama3.1:8b
   ```

## 💻 Usage
Fire up Jupyter Notebook from your terminal and start running the cells!
```bash
jupyter notebook
```
