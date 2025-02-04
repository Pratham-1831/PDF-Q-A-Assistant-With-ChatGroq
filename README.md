# Research Paper QA Assistant with ChatGroq

A Streamlit-based application that allows you to ask questions about research papers using ChatGroq's LPU inference engine and semantic search capabilities.


## Features

- **PDF Document Ingestion** from a directory
- **Text Embeddings** using HuggingFace models
- **Vector Similarity Search** powered by FAISS
- **Natural Language Queries** answered by ChatGroq's LLM (Mixtral 8x7B)
- **Streamlit Web Interface** for easy interaction

## Technologies Used

- **LangChain**: Document processing and chaining
- **HuggingFace**: Sentence Transformers for embeddings
- **FAISS**: Vector storage and similarity search
- **Streamlit**: Web interface development
- **ChatGroq**: LLM inference engine

## Prerequisites

- Python 3.8+
- [Groq API Key](https://console.groq.com/keys)
- Create a `research_papers` directory containing PDF files

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Pratham-1831/PDF-Q-A-Assistant-With-ChatGroq.git
   cd PDF-Q-A-Assistant-With-ChatGroq
2.**Install required packages**:
    pip install streamlit langchain-groq langchain-huggingface sentence-transformers faiss-cpu pypdf python-dotenv

3**Configure environment**:
    Create .env file with:
    GROQ_API_KEY=your_groq_api_key_here
    Add PDF files to the research_papers directory

##Usage
 Start the application:
      streamlit run app.py

In the Streamlit interface:

Click "Document Embedding" to process PDFs

Enter your question in the text input field

View answers with source document references

Note: First-time document processing may take a few minutes depending on the number/size of PDFs.
