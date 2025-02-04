Research Paper QA Assistant with ChatGroq
A Streamlit-based application that allows you to ask questions about research papers using ChatGroq's LPU inference engine and semantic search capabilities.
Features
-PDF document ingestion from directory
-Text embeddings using HuggingFace models
-Vector similarity search with FAISS
-Natural language queries answered by ChatGroq's LLM (Mixtral 8x7B)
-Streamlit web interface

Technologies Used
-LangChain (Document processing/chaining)
-HuggingFace (Sentence Transformers for embeddings)
-FAISS (Vector storage/similarity search)
-Streamlit (Web interface)
-ChatGroq (LLM inference)

Prerequisites
-Python 3.8+
-Groq API Key
-Create research_papers directory with PDF files
-Install required packages: 
   pip install streamlit langchain-groq langchain-huggingface sentence-transformers faiss-cpu pypdf python-dotenv

Installation & Setup
    Clone repository:git clone https://github.com/Pratham-1831/PDF-Q-A-Assistant-With-ChatGroq.git

Install dependencies:
    pip install -r requirements.txt

Create .env file:
    GROQ_API_KEY=your_groq_api_key_here

Add research papers:
    mkdir research_papers
    # Add your PDF files to this directory

Usage
Start the application:
 -streamlit run app.py
 -In the Streamlit interface:
     Click "Document Embedding" to process PDFs
     Enter your question in the text input
     View answers with source document references
  

