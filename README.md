# Smart Class Attendance System (Face Recognition)

## 📌 Project Overview
The Smart Class Attendance System is a computer vision–based application that automates classroom attendance using **real-time face recognition**. The system captures live video from a webcam, identifies known faces using pre-stored images, and automatically records attendance with date and time.

This project demonstrates practical implementation of **face recognition, image encoding, and real-time video processing** using Python and OpenCV.

---

## 🎯 Objectives
- Automate attendance marking using face recognition  
- Reduce manual effort and human error in attendance systems  
- Apply computer vision techniques in a real-world academic use case  
- Understand end-to-end workflow of real-time face recognition systems  

---

## 🧠 Problem Statement
Traditional attendance systems are time-consuming and prone to proxy attendance. This project aims to solve that problem by using facial recognition technology to identify students automatically and mark attendance only once per session.

---

## 🛠️ Technologies & Libraries Used
- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Face Recognition:** face_recognition (dlib-based)  
- **Numerical Processing:** NumPy  
- **Date & Time Handling:** datetime  
- **Development Environment:** Python script / Jupyter Notebook  

---

## ⚙️ System Workflow
1. Load known student images from the `images/` directory  
2. Extract and encode facial features from stored images  
3. Access webcam feed in real time  
4. Detect faces in each video frame  
5. Compare detected faces with known encodings  
6. Identify matching faces  
7. Mark attendance with name, time, and date  
8. Display recognition results on live webcam feed  

---

## 🗂 Directory Structure
Smart Class Attendance System/
images/ # Known face images (student images)
Attendance data/
 └── attendence_excel.xls # Attendance record file
Main2.py # Main Python script
Main_Code.ipynb # Notebook version
README.md
