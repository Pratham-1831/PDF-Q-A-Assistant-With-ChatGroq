Research Paper QA Assistant with ChatGroq

A Streamlit-based application that allows you to ask questions about research papers using ChatGroq's LPU inference engine and semantic search capabilities.

Features

PDF document ingestion from a directory.
Text embeddings using HuggingFace models.
Vector similarity search powered by FAISS.
Natural language queries answered by ChatGroq's LLM (Mixtral 8x7B).
Streamlit web interface for easy interaction.



Technologies Used
LangChain: Document processing and chaining.
HuggingFace: Sentence Transformers for embeddings.
FAISS: Vector storage and similarity search.
Streamlit: Web interface.
ChatGroq: LLM inference.


Prerequisites
Python 3.8+
Groq API Key
A research_papers directory containing PDF files.

Required Python packages: pip install streamlit langchain-groq langchain-huggingface sentence-transformers faiss-cpu pypdf python-dotenv

Installation & Setup

Clone the repository:

git clone https://github.com/Pratham-1831/PDF-Q-A-Assistant-With-ChatGroq.git

Navigate into the directory:

cd PDF-Q-A-Assistant-With-ChatGroq

Install dependencies:

pip install -r requirements.txt

Create a .env file with the following content:

GROQ_API_KEY=your_groq_api_key_here

Add research papers:

Create a directory named research_papers.

Add your PDF files to the research_papers directory.

Usage

Start the application:

streamlit run app.py

Using the Streamlit interface:
Click "Document Embedding" to process PDFs.

Enter your question in the text input field.

View answers with source document references.
