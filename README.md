# OCR Code Using Google's Document AI

## Overview

This project implements Optical Character Recognition (OCR) using Google's Document AI API to extract text and data from documents efficiently and accurately.

### Features
- **Cloud-Based OCR**: Leverages Google Cloud's Document AI API for robust text extraction.
- **Bounding Box Integration**: Extracts text within specific bounding polygons for structured data processing.
- **Excel Export**: Processes JSON outputs and transforms the extracted data into organized Excel files for easy analysis.

---

## Process Overview

1. **Research Phase**: Began by understanding OCR technology and the fundamentals of machine learning for text extraction.
2. **Initial Attempts**: Attempted to create a custom OCR program from scratch but encountered challenges in handling complex document layouts.
3. **Document AI Implementation**: Transitioned to using Google’s Document AI API, which provided accurate text extraction and bounding box capabilities.
4. **Data Transformation**: Processed JSON outputs from Document AI to create structured and meaningful Excel files.
5. **Final Code Development**: Refined the workflow to handle various document types and optimized for efficiency.

---

## How It Works
1. Upload the document image or PDF to a Google Cloud Storage bucket.
2. Use the Python script to send the document to the Document AI API.
3. Parse the JSON output to extract text based on bounding polygons.
4. Transform the extracted data into an Excel file for user-friendly visualization.

---

## Results

- Successfully extracted text and data from complex document layouts.
- Streamlined data export to Excel for further analysis.
- Demonstrated the flexibility and power of Google’s Document AI API in real-world applications.

---

## Future Improvements

- Automate the process for batch document processing.
- Enhance error handling for missing or incomplete data.
- Incorporate additional post-processing to refine the extracted data.

---

This project highlights the power of combining cloud-based AI tools with Python programming to solve practical problems in document processing.
