# AI-DEFECT-DETECTION
AI-based defect detection system using computer vision and machine learning

## 📌 Overview
The **AI Defect Detection System** is a computer vision-based application designed to automatically identify and classify defects in images. This project leverages machine learning and image processing techniques to improve accuracy, consistency, and efficiency in quality inspection processes.

Developed as part of an internship at **MindfulAI Technologies**, this project demonstrates the practical application of Artificial Intelligence in real-world industrial scenarios such as manufacturing and quality control.

---

##  Objectives
- Automate defect detection using AI
- Reduce manual inspection effort and human error
- Provide real-time predictions with confidence scores
- Build a scalable and deployable inspection system

---

##  Features
-  Image Upload Interface
-  AI-Based Defect Classification
-  Confidence Score Display
-  Real-Time Prediction System
-  Alert/Notification Integration (SMS/Console)
-  Web-based Interface using Flask

---

##  Tech Stack

###  Programming Language
- Python

###  Libraries & Frameworks
- Flask (Web Framework)
- OpenCV (Image Processing)
- NumPy (Numerical Computation)
- Pandas (Data Handling)
- Scikit-learn (Machine Learning)

###  Tools
- Git & GitHub (Version Control)
- VS Code (Development Environment)

---

##  System Architecture

1. **Image Input**
   - User uploads an image via the web interface

2. **Preprocessing**
   - Image resizing, normalization, and enhancement

3. **Model Prediction**
   - Trained ML model analyzes the image

4. **Output**
   - Displays defect type along with confidence score

5. **Alert System**
   - Sends notification if defect is detected

---

## 📂 Project Structure
AI-Defect-Detection/

│── app.py # Main Flask application

│── model/ # Trained ML model files

│── utils/ # Helper functions (prediction, alerts)

│── templates/ # HTML files

│── uploads/ # Uploaded images

│── testing_dataset/ # test images

│── requirements.txt # Dependencies

│── README.md # Project documentation


---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/AI-Defect-Detection.git
cd AI-Defect-Detection
