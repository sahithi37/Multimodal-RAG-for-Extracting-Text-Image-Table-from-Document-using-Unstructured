Multimodal RAG for Document Processing
Overview
This project implements a Multimodal Retrieval-Augmented Generation (RAG) pipeline to efficiently extract and process text, images, and tables from documents (PDFs). The solution leverages OCR (Tesseract) and Unstructured to categorize and retrieve multimodal content for downstream applications like AI-driven document analysis.

Features
Extracts text, images, and tables from PDFs.
Categorizes content into headers, footers, titles, tables, and images.
Uses Tesseract-OCR for high-accuracy text extraction.
Supports structured document processing for downstream applications.
Tech Stack
Programming Language: Python
Libraries & Tools:
Unstructured (for PDF parsing)
Tesseract-OCR (for text recognition)
Poppler (PDF utilities)
Matplotlib (visualization)
Installation
Clone the repository:
bash
Copy
Edit
git clone <repository-link>
cd <project-folder>
Install dependencies:
bash
Copy
Edit
pip install "unstructured[all-docs]" pillow pydantic lxml matplotlib  
sudo apt-get update  
sudo apt-get install poppler-utils libleptonica-dev tesseract-ocr libtesseract-dev python3-pil  
pip install unstructured-pytesseract  
