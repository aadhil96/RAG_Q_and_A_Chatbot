# RAG Document Q&A With Groq and Llama3.1

This project is a web-based question-answering (Q&A) application built using **Streamlit**, **LangChain**, **Groq API**, and **Llama3.1 model**. The app allows users to load a set of research papers (PDF files), create embeddings of the document contents using **FAISS** (a vector search engine), and perform retrieval-augmented generation (RAG) by querying the research papers for specific information. The model answers the user's questions based on the context of the documents.

## Screenshot 

Capture.JPG

## Features

- Load research papers in PDF format and create vector embeddings of the documents.
- Retrieve document content using FAISS (vector store) and LangChain's document retrieval pipeline.
- Integrate the **Groq API** with the **Llama3.1-8B** model to provide accurate and context-aware answers to user queries.
- Display the search results and response times for each query.
- Search through the content of the documents for specific queries and view relevant document excerpts with a similarity search.

## Requirements

1. Python 3.8 or higher
2. Required libraries:
   - Streamlit
   - LangChain
   - OpenAI
   - FAISS
   - dotenv (for API key management)
   - time
   - PyPDF2 (for PDF document loading)

## Installation

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone <repo-link>
   cd <repo-directory>
   
2. Install the necessary Python dependencies:

    ```bash
   pip install -r requirements.txt

3. Create a .env file in the project root and set the following environment variables with your OpenAI and Groq API keys:

     ```bash
     OPENAI_API_KEY=your_openai_api_key
    GROQ_API_KEY=your_groq_api_key

