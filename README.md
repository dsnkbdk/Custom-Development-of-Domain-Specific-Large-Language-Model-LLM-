# Domain-Specific Large Language Model

## Overview
This project sets up a Retrieval-Augmented Generation (RAG) pipeline utilizing the "mistral" model from Ollama. The notebook includes steps to install necessary dependencies, run the model in the background, and manage the asynchronous execution of tasks.

## Key Features
- **Thread Management**: Employs Python's `threading` module to run background tasks without blocking the main thread of execution.
- **Large Language Models (LLM)**: Integrates and runs large language models, specifically the "mistral" model provided by Ollama.

## Dependencies
The following packages are required for this project:
- `langchain`
- `beautifulsoup4`
- `chromadb`
- `gradio`
- `pypdf`
- `ollama`

## Setup Instructions
1. **Install Dependencies**: Ensure all required packages are installed.
2. **Run Ollama Model**: Follow the notebook instructions to run the "mistral" model in the background using asynchronous programming and threading.
3. **Manage Processes**: Use the provided commands to handle the Ollama processes, ensuring smooth execution and handling unresponsive states.

## Usage
The notebook guides you through setting up the RAG pipeline, running the model, and managing processes. Ensure you follow the instructions carefully to avoid blocking execution and to handle the Ollama service effectively.
