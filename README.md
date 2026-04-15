# 🚀 DataMaster AI

**Intelligent Data Entry & Cleaning Automation**

DataMaster AI is a full-stack web application designed to eliminate manual data entry. It ingests unstructured data from images, scanned documents, and messy spreadsheets, utilizes Cloud AI OCR to extract tables, and automatically cleans and organizes the output. Users can instantly export their structured data into 7 different formats or safely append it to their existing legacy databases.

## ✨ Key Features

* **Omni-Channel Ingestion:** Upload directly from `.png`, `.jpg`, `.pdf`, `.csv`, `.xlsx`, `.docx`, `.json`, and `.txt` files.
* **AI-Powered OCR Engine:** Integrates with the OCR.space API to read flat images. Includes a custom-built PDF Slicer that silently chunks massive PDFs to bypass standard API constraints.
* **Automated Data Scrubbing:** Automatically drops empty rows/columns, detects natural headers, and scrubs illegal XML control characters to prevent downstream database crashes.
* **Smart Append Technology:** Safely inject new rows directly to the bottom of existing Excel or CSV files without overwriting legacy data.
* **Multi-Format Export:** Download cleaned data instantly as Excel, CSV, JSON, TXT, Word Documents, PDF reports, or high-resolution PNG images.
* **Responsive UI:** Built with Tailwind CSS for a seamless experience across desktop, tablet, and mobile devices. Includes strict upload shields (10MB limit) and loading state protections.

## 🛠️ Technical Architecture

**Frontend:**
* HTML5 & Vanilla JavaScript
* Tailwind CSS (Utility-first styling)

**Backend:**
* Python 3.11
* Flask (Web Server & Routing)
* Pandas & OpenPyxl (Heavy Data Crunching & Excel manipulation)
* PyPDF2 (PDF parsing and chunking)
* python-docx, fpdf2, matplotlib (Multi-format generation)

**External APIs:**
* OCR.space REST API

## Authors
* **Ashmit Prusty** - *Backend & AI Integration* 
* **Ayushman Tripathy** - *Frontend & Cloud Deployment*

  Available at URL-- https://data-bot-web-h7c4.onrender.com
