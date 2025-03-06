# MultimodalRAG
An AI-powered assistant that retrieves and processes information from a multi-modal knowledge base consisting of documents (PDF, DOCX), images, and videos.
# Features
Extracts text from PDFs, Word documents, images (OCR), and videos (speech-to-text).

Stores and retrieves data using FAISS and Sentence Transformers.

Uses a Retrieval-Augmented Generation (RAG) model for accurate answers.

Provides a web-based UI using Gradio.
# Installation
## Step 1: Clone the Repository

git clone https://github.com/sid-4998/MultimodalRAG.git

cd MultimodalRAG

## Step 2: Install Dependencies

pip install -r requirements.txt

## Step 3: Run the AI Assistant

python src/main.py

This will launch the Gradio UI where users can ask questions.

# Usage

Place documents, images, and videos inside the data folder.

Run main.py to index and process the data.

Use the web UI to ask questions.
