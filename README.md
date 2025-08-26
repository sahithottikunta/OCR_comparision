# 📝 OCR Comparison

This repository contains a Jupyter Notebook (`OCR_Comparision.ipynb`) that demonstrates how to **compare the outputs of multiple OCR (Optical Character Recognition) engines** on scanned or digital documents.  
The goal is to evaluate the quality of text extraction, highlight differences, and analyze which engine is more reliable for different document types.

## 🚀 Features
- Run multiple OCR engines (e.g., Tesseract, EasyOCR, PaddleOCR, etc.).
- Compare extracted text side by side.
- Highlight strengths and weaknesses of each tool.
- Provide visual previews and structured comparisons.
- Useful for selecting the best OCR engine for downstream document analysis.

## 📂 Project Structure
.
├── OCR_Comparision.ipynb # Notebook with OCR comparison logic
└── README.md # Project documentation

## 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Recommended OCR libraries (depending on which engines you want to test):
  ```bash
  pip install pytesseract easyocr paddleocr matplotlib
Install Tesseract OCR engine (if using Tesseract):

sudo apt install tesseract-ocr

Usage

Clone this repository:

git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>


Place your input documents (scanned PDFs/images) inside a sample_docs/ folder.

Open the notebook:

jupyter notebook OCR_Comparision.ipynb


Update the notebook cells with the OCR engines you want to run.

Execute all cells to:

Extract text using different OCR engines.

Compare and visualize the results.

Save structured comparisons for analysis.

📊 Example Output
🔹 Tesseract OCR
This is an example line from a scanned PDF.

🔹 EasyOCR
This is an exarnple line from a scarnned PDF.

🔹 PaddleOCR
This is an example line from a scanned PDF.


👉 From the comparison above, Tesseract and PaddleOCR produced cleaner text, while EasyOCR introduced errors.

📌 Workflow

1)Load scanned or digital PDF/image.

2)Apply multiple OCR engines.

3)Compare results (line by line or word by word).

4)Document strengths/weaknesses for each engine.

🤝 Contributing

This is done for my analysis of different ocr tools.

⚖️ License

All Rights Reserved.
This project is for personal, academic, or internal use. You may not copy, modify, distribute, or use it commercially without explicit permission.


---

Do you want me to also **merge this README with your previous one** so that your repo can cover both projects (`Analyze_a_scanned_PDF.ipynb` and `OCR_Comparision.ipynb`) under a single structured README? ​:contentReference[oaicite:0]{index=0}​
