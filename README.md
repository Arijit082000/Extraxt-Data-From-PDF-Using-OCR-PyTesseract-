#  PDF Data Extraction Using PyTesseract

<div align="center">

#  OCR-Based PDF Data Extraction and CSV Generation

Extract structured information from scanned PDF documents using **PyTesseract OCR**, **pdf2image**, **Regular Expressions**, and **Pandas**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![OCR](https://img.shields.io/badge/OCR-Tesseract-green)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-purple?logo=pandas)
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-orange)

</div>

---

#  Project Overview

This project automates the extraction of text from scanned PDF documents using **PyTesseract OCR**. The extracted text is processed with **Regular Expressions (Regex)** to identify semester-wise subject names and marks. Finally, the cleaned and structured data is exported to **Excel (.xlsx)** and **CSV (.csv)** formats.

This workflow is especially useful for digitizing scanned academic mark sheets and converting them into structured datasets for further analysis.

---

#  Objectives

- Extract text from scanned PDF files.
- Perform OCR using Tesseract.
- Process multiple PDFs automatically.
- Organize extracted information into structured tables.
- Export results to Excel and CSV.

---

#  Features

-  Batch processing of multiple PDF files
-  OCR using PyTesseract
-  Convert PDF pages into high-resolution images
-  Extract text from each page
-  Clean extracted text using Regex
-  Create structured DataFrames
-  Export results to Excel and CSV
-  Google Drive integration for input/output

---

#  Technologies Used

- Python
- PyTesseract
- pdf2image
- Pandas
- Regular Expressions (Regex)
- OpenPyXL
- Google Colab

---

#  Project Workflow

1. Mount Google Drive
2. Install required packages
3. Convert PDF pages to images
4. Perform OCR using Tesseract
5. Extract text from every PDF
6. Store extracted text in a DataFrame
7. Save extracted text as Excel
8. Read Excel for further processing
9. Extract semester, subject names and marks using Regex
10. Sort semester-wise data
11. Export final structured dataset as CSV

---

#  Required Libraries

```bash
pip install pdf2image pytesseract pandas openpyxl pillow
```

Install system packages (Google Colab):

```bash
apt-get install poppler-utils
apt-get install tesseract-ocr
apt-get install tesseract-ocr-ben
```

---

#  Input

- Multiple scanned PDF documents
- Academic mark sheets

---

#  Output

## Excel

```
Extracted_Data.xlsx
```

Contains OCR extracted raw text.

## CSV

```
Subject_Wise_Marks.csv
```

Contains cleaned semester-wise structured subject and marks data.

---

#  Data Processing

The project uses:

- OCR
- Regex pattern matching
- Data cleaning
- DataFrame manipulation
- Sorting by semester
- CSV generation

---

#  Repository Structure

```text
.
├── PDF Data Extraction Using PyTesseract.ipynb
├── README.md
```

---

#  How to Run

1. Open the notebook in Google Colab.
2. Mount Google Drive.
3. Upload PDF files into the input folder.
4. Run all notebook cells sequentially.
5. Download the generated Excel and CSV files.

---

#  Future Improvements

- GUI using Streamlit
- Support additional document formats
- Improve OCR accuracy with image preprocessing
- Automatic table extraction
- Multi-language OCR support
- Cloud deployment

---

#  Author

**Arijit Dasgupta**

Data Analytics | Machine Learning | OCR Automation

---


