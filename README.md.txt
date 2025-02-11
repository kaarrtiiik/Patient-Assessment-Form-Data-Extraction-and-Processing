README.md

# Patient Assessment Form Data Extraction and Processing

## Overview

This project provides a Python-based solution for extracting text from scanned patient assessment forms (JPEG/PDF) using OCR, parsing and structuring the extracted data into JSON format, and storing the structured data in a SQL database.

## Requirements

* Python 3.8+
* `pytesseract` for OCR
* `pdf2image` for PDF conversion
* `Pillow` for image processing
* `json` for JSON output
* `sqlite3` for SQL database storage

## Usage

1. Install required libraries using `pip install -r requirements.txt`
2. Run `extract_data.py` using `python extract_data.py`
3. View extracted data in `sample_output.json`
4. View database schema in `database_schema.sql`