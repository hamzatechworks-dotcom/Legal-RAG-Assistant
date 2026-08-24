# Legal-RAG-Assistant
A Legal RAG Assistant designed to help users find and understand information related to Pakistan's Constitution, laws, and legal sections. The system uses Retrieval-Augmented Generation (RAG) to provide answers based on uploaded legal documents instead of relying only on the LLM's general knowledge.

# Features
Ask legal questions in natural language
Retrieves relevant information from legal PDFs
Provides answers based on the available documents
Shows the reference/source used to generate the answer
Helps users quickly find relevant laws and sections
Simple and user-friendly Gradio interface

# Tech Stack
Python
Google Gemini API
Gemini Embeddings
ChromaDB for vector storage
LangChain for the RAG pipeline
Gradio for the user interface

# How It Works
Legal PDFs are loaded into the system.
Documents are divided into smaller chunks.
The chunks are converted into embeddings and stored in ChromaDB.
When a user asks a question, the system retrieves the most relevant legal information.
Gemini generates an answer using the retrieved context.
The relevant source/reference is shown along with the response.


# Note: This project is for educational and informational purposes and should not be considered a substitute for professional legal advice.
