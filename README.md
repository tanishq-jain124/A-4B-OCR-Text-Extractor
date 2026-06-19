# A-4B-OCR-Text-Extractor
# 🖼️ OCR Image Text Extraction using Python & Tesseract

## 📌 Project Overview

This project is a simple Optical Character Recognition (OCR) application built in Python using **Tesseract OCR** and **Pytesseract**. It allows users to upload an image and automatically extract any readable text contained within it.

The notebook is designed for **Google Colab**, making it easy to run without local setup.

---

## 🚀 Features

* Upload image files directly from your browser
* Extract text from images using OCR
* Supports printed text recognition
* Simple and beginner-friendly implementation
* Runs entirely in Google Colab
* Error handling for invalid or unreadable files

---

## 🛠️ Technologies Used

* Python
* Tesseract OCR Engine
* Pytesseract
* Pillow (PIL)
* Google Colab

---

## 📂 Project Structure

```text
Assignment_04_B.ipynb
│
├── Install Tesseract OCR
├── Import Required Libraries
├── Upload Image
├── Process Image
├── Extract Text using OCR
└── Display Results
```

---

## 📦 Required Libraries

The notebook automatically installs:

```python
!sudo apt-get update -qq
!sudo apt-get install tesseract-ocr -qq
!pip install pytesseract Pillow -qq
```

---

## ▶️ How to Run

### Step 1: Open in Google Colab

Upload the notebook to Google Colab.

### Step 2: Run the Notebook

Execute the cell to install dependencies and start the upload interface.

### Step 3: Upload an Image

Click the upload button and select an image containing text.

### Step 4: View Extracted Text

The OCR engine will process the image and display the detected text.

---

## 💻 Example

### Input Image

```text
Hello World
Welcome to OCR
```

### Output

```text
Hello World
Welcome to OCR
```

---

## 🔍 How It Works

1. User uploads an image.
2. The image is loaded into memory using Pillow.
3. Tesseract OCR scans the image.
4. Detected text is extracted.
5. Results are displayed in the notebook output.

---

## ⚠️ Limitations

* Works best with clear, high-resolution images.
* Handwritten text may not be accurately recognized.
* Complex backgrounds can reduce OCR accuracy.
* Supports primarily printed text.

---

## 📈 Future Improvements

* Support PDF files
* Multi-language OCR
* Image preprocessing for better accuracy
* Export extracted text to TXT or PDF
* Web-based user interface using Streamlit or Flask
* Batch processing of multiple images

---

## 📜 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

Created as part of an OCR and Image Processing assignment using Python and Tesseract OCR.
