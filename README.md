# Fraud-Detection-Using-Machine-Learning
We have seen that Accuracy of both Random Forest and Decision Tree is equal, although the precision of Random Forest is more. In a fraud detection model, Precision is highly important because rather than predicting normal transactions correctly we want Fraud transactions to be predicted correctly and Legit to be left off.
⚡ How to Use
Place your PDF (e.g., Olympiad sample paper) in the project folder.

Open the Python script (tempCodeRunnerFile.py).

Set your PDF filename in the script:

python
Copy
Edit
pdf_path = "your_file.pdf"  # Change to your actual PDF filename
Run the script:

bash
Copy
Edit
python tempCodeRunnerFile.py
✅ That’s it!

Extracted images will be saved in extracted_images/

Structured output will be saved in pdf_extracted_content.json

# 📄 PDF Content Analysis and Question Generation

This project is designed to extract structured content (text and images) from educational PDFs (e.g., Olympiad sample papers), and organize it in a JSON format for AI-based question generation.

---

## 📌 Project Overview

**Objective**: Build a Python-based system that:
1. Extracts all text and images from a given PDF.
2. Structures the extracted content page-wise.
3. Saves the results into a clean, easy-to-use `JSON` file.

---

## 📁 Project Structure

PDF-Content-Analysis-and-Extraction/
│
├── extracted_images/ # Automatically created to store extracted images
├── pdf_extracted_content.json # Final JSON output of all pages
├── tempCodeRunnerFile.py # Main Python script
├── README.md # This documentation

yaml
Copy
Edit

---

## 🔧 Technologies & Libraries Used

- **Python 3.12+**
- [`PyMuPDF (fitz)`](https://pymupdf.readthedocs.io/en/latest/)
- [`json`](https://docs.python.org/3/library/json.html)
- [`os`](https://docs.python.org/3/library/os.html)

---

## ⚙️ Setup Instructions

### ✅ 1. Clone the repository or download the files

```bash
git clone https://github.com/yourusername/PDF-Content-Analysis-and-Extraction.git
cd PDF-Content-Analysis-and-Extraction
✅ 2. Create and activate a virtual environment (recommended)
bash
Copy
Edit
python -m venv venv
# Activate it
venv\Scripts\activate         # Windows
source venv/bin/activate      # macOS/Linux
✅ 3. Install dependencies
bash
Copy
Edit
pip install PyMuPDF
🚀 How to Run
Replace the pdf_path in tempCodeRunnerFile.py with your target PDF file.

bash
Copy
Edit
python tempCodeRunnerFile.py
Extracted images will be saved in the extracted_images/ folder.

Structured content will be saved in pdf_extracted_content.json.

📦 Sample JSON Output
json
Copy
Edit
[
  {
    "page": 1,
    "text": "Q1. What comes next in the pattern?",
    "images": [
      "extracted_images/page1_img1.png"
    ]
  },
  {
    "page": 2,
    "text": "Q2. Identify the odd one out.",
    "images": []
  }
]
🤖 Future Scope
Apply OCR or AI models to interpret image content.

Use LLMs (like GPT or LLaMA) to generate MCQs or explain visuals.

Build a frontend interface for educators to auto-generate quiz banks.

🧠 Credits
This project is part of an AI/Python Internship Assignment focused on PDF content analysis and AI-based question generation.

📬 Contact
Siddhant Godwani
📧 siddhantgodwani8697@gmail.com
[🔗 LinkedIn :](https://www.linkedin.com/in/siddhant-godwani)
