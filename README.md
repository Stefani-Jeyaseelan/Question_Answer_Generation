# Enhancing Question Answer Generation from PDFs

## Overview
This project focuses on enhancing the process of generating questions and answers from PDF documents. By leveraging advanced natural language processing (NLP) models, the system aims to automate the extraction of meaningful questions and corresponding answers from textual data, facilitating easier access to information.

## Features
- **PDF Summarization**: Utilizes BERT to summarize the contents of PDF files.
- **Question Generation**: Employs T5 to generate relevant questions based on the summarized text.
- **Answer Extraction**: Utilizes DistilBERT to extract accurate answers for the generated questions.
- **Keyword Extraction**: Implements RAKE to extract key terms from the documents.

## Technologies Used
- Python
- BERT
- T5
- DistilBERT
- RAKE
- PyTorch / TensorFlow (depending on implementation)
- PDF Processing Libraries (e.g., PyMuPDF, pdfminer)
