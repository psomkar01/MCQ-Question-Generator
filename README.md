# MCQ-Question-Generator

# MCQ Question Builder

## 📖 **Project Overview**
MCQ Question Builder is a Flask-based web application designed to generate Multiple Choice Questions (MCQs) from uploaded text files. 
It simplifies the process of creating quizzes by automatically extracting text from documents (PDF, DOCX, or TXT) and generating MCQs with options and answers.
Users can download the generated MCQs as a text file or a PDF for easy access and sharing.

### **Key Features**
- Upload documents in PDF, DOCX, or TXT formats.
- Extract text from the uploaded files.
- Generate a specified number of MCQs from the extracted content.
- Download MCQs in TXT or PDF format.
- Simple and user-friendly web interface.

---

## 🛠 **Tools Used**
1. **Framework**: Flask
2. **Text Extraction**:
   - `pdfplumber` for extracting text from PDFs.
   - `python-docx` for extracting text from DOCX files.
3. **Question Generation**: Google Generative AI (`gemini-1.5-pro` model).
4. **PDF Creation**: `fpdf` library for formatting and exporting MCQs to PDF.
5. **File Handling**: Built-in Python modules like `os` and `werkzeug`.

---

## 💻 **Technologies Used**
1. **Backend**: 
   - Python
   - Flask (for creating web routes and handling requests)
2. **Frontend**: 
   - HTML
   - CSS (for styling)
3. **APIs**: 
   - Google Generative AI for generating MCQs from text.
4. **Libraries**:
   - `pdfplumber` for PDF text extraction.
   - `python-docx` for Word document processing.
   - `fpdf` for generating PDFs.

---

## 🚀 **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mcq-question-builder.git
   cd mcq-question-builder

---

## Folder Structure
MCQ Question Builder/
├── app.py                 # Main Flask application
├── templates/             # HTML files
│   ├── index.html
│   ├── results.html
├── uploads/               # Folder for uploaded files
├── results/               # Folder for generated files (TXT, PDF)
├── venv/                  # Virtual environment (optional)
├── requirements.txt       # Python dependencies



