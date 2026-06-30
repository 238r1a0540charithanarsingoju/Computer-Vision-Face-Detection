# 📷 Real-Time Face Detection using OpenCV

## 📌 Overview

This project implements a **real-time face detection system** using **OpenCV** and the **Haar Cascade Classifier**. It captures live video from the webcam, detects human faces, and draws bounding boxes around them in real time.

---

## 🎯 Objectives

* Access the webcam using OpenCV
* Detect human faces in real time
* Draw bounding boxes around detected faces
* Learn the fundamentals of Computer Vision

---

## 🚀 Features

* 📷 Real-time webcam access
* 😊 Face detection using Haar Cascade Classifier
* 🟩 Bounding boxes around detected faces
* ⚡ Fast and lightweight implementation
* ❌ Press **Q** to exit the application

---

## 🛠️ Technologies Used

* Python
* OpenCV
* Haar Cascade Classifier

---

## 📁 Project Structure

```text
Computer_Vision_Face_Detection/
│
├── haarcascade/
│   └── haarcascade_frontalface_default.xml
│
├── src/
│   └── face_detection.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd Computer_Vision_Face_Detection
```

### 2. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📥 Download Haar Cascade File

Download the file:

```text
haarcascade_frontalface_default.xml
```

Place it inside the `haarcascade/` folder.

---

## ▶️ Run the Project

```bash
python src/face_detection.py
```

---

## 🔄 Workflow

```text
Start Webcam
      │
      ▼
Capture Video Frame
      │
      ▼
Convert Frame to Grayscale
      │
      ▼
Detect Faces
      │
      ▼
Draw Bounding Boxes
      │
      ▼
Display Live Video
```

---

## 📚 Skills Demonstrated

* Computer Vision
* Real-Time Video Processing
* Face Detection
* Image Processing
* OpenCV
* Python Programming

---

## 🔮 Future Enhancements

* Face Recognition
* Eye Detection
* Smile Detection
* Emotion Recognition
* Face Mask Detection
* Attendance System

---

## 👨‍💻 Author

This project was developed as part of an AI & Machine Learning learning roadmap to gain practical experience in Computer Vision using OpenCV.
