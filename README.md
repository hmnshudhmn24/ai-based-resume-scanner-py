# AI-Based Resume Scanner

A Python-based Resume Scanner that extracts key details such as **Name, Email, Phone, and Skills** from resumes (PDF/DOCX) using **NLP (spaCy)** and **PDF parsing (pdfplumber)**.

## Features

- Extracts Name, Email, Phone Number, and Skills
- Supports PDF and DOCX formats
- Uses spaCy NLP for Named Entity Recognition (NER)
- Saves extracted details in a structured JSON file

## Installation

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

Run the program:

```bash
python resume_scanner.py
```

Enter the file path of the resume when prompted. The extracted details will be displayed and saved in `extracted_resume_details.json`.

## Supported File Formats

- `.pdf` (Extracted using pdfplumber)
- `.docx` (Extracted using python-docx)
