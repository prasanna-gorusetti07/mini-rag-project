# Mini RAG Project

## About the Project
Mini RAG (Retrieval-Augmented Generation) is a Python-based project that retrieves relevant information from documents and helps users find answers to their questions.

## Features
- Document text processing
- Text chunking
- Text embeddings generation
- Semantic search using FAISS
- Relevant document retrieval
- Question answering workflow

## Technologies Used
- Python
- FAISS
- Hugging Face Transformers
- Sentence Transformers
- Embeddings

## Project Structure

```text
mini-rag-project/
│
├── app.py
├── query.py
├── requirements.txt
├── documents/
└── vectorstore/
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/prasanna-gorusetti07/mini-rag-project.git
```

2. Open the project folder:

```bash
cd mini-rag-project
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
python app.py
```

## How It Works
1. Reads documents.
2. Splits text into smaller chunks.
3. Generates embeddings.
4. Stores vectors using FAISS.
5. Retrieves relevant information based on user questions.

## Author
Prasanna Gorusetti

## Project Type
Python | AI | Machine Learning | RAG
