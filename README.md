Automatic Document Translation using NLP (Transformer)

This project is a web application for automatic document translation built with Python and Streamlit.
It allows users to upload PDF or Word (DOCX) files, translate their content between multiple languages, and download the translated document in both Word and PDF formats.
The translation is powered by a pre-trained Transformer-based neural machine translation model from Helsinki-NLP (MarianMT) available on Hugging Face.

->Features
Upload PDF or Word documents
Automatic text extraction from documents
Language selection (source & target)
Neural machine translation using Transformer (Encoder–Decoder) architecture
Batch processing for long documents
Generate translated DOCX and PDF files
Simple and interactive UI with Streamlit

->Technologies Used
Python
Streamlit – web interface
Hugging Face Transformers
MarianMT (Helsinki-NLP)
pdfplumber – PDF text extraction
python-docx – Word file handling
ReportLab – PDF generation

 Translation Pipeline:
Document (PDF/DOCX)
        ↓
Text Extraction
        ↓
Tokenization
        ↓
Transformer-based Translation Model
        ↓
Decoded Translated Text
        ↓
Generated Word & PDF Files

->Notes
This project uses a specialized NLP translation model, not a general-purpose LLM (e.g., GPT).
The model is pre-trained and does not require fine-tuning.
Performance depends on document length and language pair.

-> Use Cases
Testing neural machine translation models
Translating academic or technical documents
NLP and Transformer architecture demonstrations
Educational projects in AI / Data Science

 Author:
Farah Banhakeia
Master’s student in Data Science & Intelligent Systems
