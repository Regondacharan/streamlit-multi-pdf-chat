# Chat with Multiple PDFs

This is a Streamlit application that allows users to upload multiple PDF files and interactively chat with their content. The app extracts text from PDFs, splits it into manageable chunks, generates semantic embeddings using OpenAI embeddings, and indexes them with FAISS for fast semantic search. LangChain powers the conversational retrieval with memory, enabling natural language questions and answers based on the document content.

## Features

- Upload and process multiple PDF documents simultaneously
- Extract, chunk, and embed PDF text for semantic search
- Interactive chat interface powered by OpenAI and LangChain
- Maintains conversation history for contextual answers
- Simple and clean UI built with Streamlit and custom HTML/CSS

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/Regondacharan/streamlit-multi-pdf-chat
    ```

2. (Optional) Create and activate a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. Install required packages:
    ```
    pip install -r requirements.txt
    ```

4. Configure environment variables as needed (e.g., OpenAI API keys) in a `.env` file.




# streamlit run document.py


- Upload PDFs in the sidebar and click "Process".
- Type questions in the input box to chat with your documents.
- View the chat responses that use document content context.

## File Overview

- `document.py`: Main app script with Streamlit UI and LangChain integration.
- `HtmlTemplate.py`: HTML and CSS templates for chat styling.
- `requirements.txt`: List of Python dependencies.
- `.env`: Environment variables file (not included).

## Technologies

- Streamlit for interactive UI
- LangChain for conversational AI
- PyPDF2 for PDF parsing
- OpenAI embeddings for semantic search
- FAISS for vector indexing and retrieval

---



## Usage

Run the app locally with Streamlit:
