# VIZORA – Computer Vision Face Analysis Tool

VIZORA is a web-based computer vision application that performs **human face detection** on images and live video streams using **OpenCV**.  
The project demonstrates how classical computer vision techniques can be integrated into a **Flask-based web application** with a modern and visually rich dashboard interface.

---

## 🚀 Features

- 📷 Image-based face detection using OpenCV  
- 🎥 Real-time face detection using webcam (local environment)  
- 🔢 Face count analysis for uploaded images  
- 🌐 Web-based interface built with Flask  
- 🎨 Modern dashboard-style UI with gradient background  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Web Framework:** Flask  
- **Frontend:** HTML, CSS  
- **Face Detection Model:** Haar Cascade Classifier (pre-trained)

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/vizora-face-analysis.git
cd vizora-face-analysis
```

### Step 2: Install Required Packages
```bash
pip install -r requirements.txt
```

### Step 3: Run the Application
```bash
python app.py
```

### Step 4: Open in Browser
http://127.0.0.1:5000/

---

## 🖼️ How It Works
1. The user uploads an image or starts webcam detection.
2. The image or video frame is converted to grayscale.
3. OpenCV’s Haar Cascade classifier is used to detect human faces.
4. Bounding boxes are drawn around detected faces.
5. The processed output is displayed on the web interface.

---

## ⚠️ Limitations
1. Webcam functionality works only in the local environment.
2. Haar Cascade performs best for frontal face images.
3. Detection accuracy may reduce in low-light or side-angle images.

---

## 🎯 Future Enhancements
1. Face blurring for privacy protection
2. Confidence score for detected faces
3. Detection history storage
4. Dark/Light theme toggle
5. Deep learning–based face detection models

---

## 📌 Use Case
This project is suitable for:
1. Learning Computer Vision fundamentals
2. Academic mini projects
3. Internship and portfolio demonstrations
4. Understanding OpenCV and Flask integration

---

## 👩‍💻 Author
## Tanisha K S


