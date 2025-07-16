
# Sanskrit to English Image Translator

This project extracts **Sanskrit text** from images using **OCR (Tesseract)** and translates it to **English** using fuzzy string matching with a custom dictionary.

## 🧰 Tech Used
- Python, OpenCV, pytesseract
- SequenceMatcher (fuzzy matching)
- Google Colab

## 💡 Features
- Image preprocessing for better OCR
- Cleans OCR output to keep only Devanagari characters
- Finds best match with confidence score
- Outputs translated word with accuracy info

## 🔧 To Run
```bash
pip install pytesseract opencv-python
!apt-get install -y tesseract-ocr
!apt-get install -y tesseract-ocr-san


---


