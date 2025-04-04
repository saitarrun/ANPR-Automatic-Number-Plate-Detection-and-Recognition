# ANPR-Automatic-Number-Plate-Detection-and-Recognition


A real-time system to detect and recognize vehicle number plates using **OpenCV**, **EasyOCR**, **TensorFlow/Keras**, and **Tesseract OCR**. This project can be used in applications such as traffic surveillance, smart parking, and security checkpoints.

---

## 📖 Project Summary

This project focuses on automatically detecting vehicle license plates from live video input (e.g., webcam feed) and recognizing the characters using OCR. By applying a mix of image processing and machine learning, it extracts number plates and decodes them into readable alphanumeric text.

> 📌 Built for GITAM University (CSE Dept) under the guidance of **Dr. Praveen Gupta**, as part of an academic research project.

---

## 🧠 Technologies Used

- **OpenCV** – Video capture and image processing
- **EasyOCR** / **Tesseract** – Optical Character Recognition
- **TensorFlow** / **Keras** – Model building (if using deep learning)
- **Python** – Core programming
- **Imutils** – Utility functions for OpenCV
- **Tkinter** – GUI (if enabled)

---

## ⚙️ Installation & Setup

### 🔧 Prerequisites

Ensure Python 3.7+ is installed.

Install [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) and add it to your system path.

### 📦 Install Required Libraries

pip install opencv-python easyocr pytesseract tensorflow keras imutils

🚀 How to Execute
___
▶️ Run the Main Program
bash
Copy
Edit
python main.py
This will:

Open your webcam

Detect number plates in real-time

Display extracted plate numbers using OCR

🧠 (Optional) Train Your Own OCR Model
bash
Copy
Edit
python train_model.py
Useful for improving accuracy based on custom datasets.

💡 Features
____________________________________________
1. Real-time detection using webcam

2. OCR with EasyOCR and Tesseract

3. Snapshot of detected plates

4. Modular structure for easy upgrades

5. Output display on frame or via terminal


🔒 Future Scope & Restrictions
________________________________________________
Planned future integrations include:
1.  Vehicle registration database validation (e.g., VAHAN)

2. Web-based dashboard with logs and analytics

3. Location & timestamp mapping

4. Mobile app & SMS alerts

⚠️ Other advanced integrations are currently under private development and restricted from public display. Please reach out for authorized access.
