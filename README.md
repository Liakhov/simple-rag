# Simple RAG App

This is a simple Retrieval-Augmented Generation (RAG) application using Python and local Ollama.

## Overview

This project implements a RAG system that utilizes local document storage and the Ollama library for text generation.

## Features

- Python-based RAG implementation
- Integration with local Ollama
- Document storage in the `data` folder

## Requirements

- Python 3.x
- Ollama library

## Setup

1. Clone this repository

2. Create and activate a virtual environment, then install the required dependencies:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt;
```

3. Place your Markdown document in the `data` folder.

4. Create an `.env` file in the root directory of the project and add the following:

```
DOCUMENT_NAME=your_document_name.md
MODEL_NAME=your_chosen_model
```
Replace `your_document_name.md` with the name of your document file, and `your_chosen_model` with the Ollama model you want to use.

5. Ensure Ollama is installed and running on your local machine.





