## Medical Assistant Chatbot
Overview
The Medical Assistant Chatbot (memory/ without memory) is an AI-driven tool designed to assist doctors by providing medical insights, understanding documents, and improving patient interactions. Built using Retrieval-Augmented Generation (RAG) technology, it allows medical professionals to upload documents, which the chatbot can process and comprehend to support decision-making.

Features
✔ Medical Document Understanding – Reads and interprets uploaded medical documents.
✔ Doctor Assistance – Provides data-driven insights to support patient care.
✔ Patient Guidance – Offers medical information based on trained knowledge.
✔ Report Generation – Assists in creating structured medical reports.

Project Structure
📂 chroma_db/ – Contains embeddings generated using the LLaMA 3.2 model.
📂 chroma-BAAI/ – Contains embeddings generated using the BAAI/bge-small-en-v1.5 model.
📄 app.py – Streamlit-based interactive chatbot interface.
📄 medmitra.ipynb – Jupyter Notebook implementation of the chatbot.
📄 B09221-eng.pdf – WHO medical document used for chatbot training.

Technology Stack
Language Model: LLaMA 3.2 & BAAI/bge-small-en-v1.5
Vector Database: ChromaDB
Frameworks: Streamlit, Jupyter Notebook
Data Source: WHO Medical Documents