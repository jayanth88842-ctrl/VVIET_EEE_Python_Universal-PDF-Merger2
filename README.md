# Universal PDF Merger

A Python-based Streamlit application that allows users to upload multiple files (PDFs, Images, and Word Documents), merges them into a single PDF, and provides a page-by-page visual preview of the final document.

## Features
- **Multi-format Support:** Merges `.pdf`, `.jpg`, `.png`, and `.docx`.
- **In-Memory Processing:** Uses `BytesIO` streams so no files are written to the server disk.
- **Visual Preview:** Renders the merged PDF page-by-page directly in the browser using `PyMuPDF`.

## Local Setup

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd pdf-merger-app
