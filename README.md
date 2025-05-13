# Document Q&A Agent API

This API enables users to upload various document types (PDF, text, images), extract and redact sensitive information (PII), index the content into a FAISS vector store using sentence embeddings, and query the documents using a Gemini-powered LangChain agent.

---

## Features

- Upload documents (.pdf, .txt, .docx, .jpg, .png, etc.)
- Automatically extract and redact PII (emails, phone numbers, IDs)
- Perform OCR on image-based documents using EasyOCR
- Store and search document content with FAISS and HuggingFace embeddings
- Query indexed documents via a Gemini-based LangChain agent
- FastAPI-powered REST interface

---

## Technologies Used

- FastAPI
- LangChain
- Google Gemini (via langchain_google_genai)
- FAISS
- HuggingFace Embeddings
- EasyOCR
- PyPDFLoader, UnstructuredLoader
- Uvicorn (development server)
- dotenv for configuration

---
