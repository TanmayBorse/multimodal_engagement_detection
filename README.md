# Real-Time Multimodal Engagement Detection in Diverse Learning Environments

This project implements a real-time system that detects learner engagement using a **multimodal approach**, combining **facial emotion recognition (CNN)** with **geometric facial metrics** like **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)**. The system works on live webcam input and outputs engagement levels along with session summaries.

---

## ✨ Features

- **Real-Time Detection** using a webcam  
- **CNN-based Facial Emotion Recognition** (7-class classification)  
- **EAR & MAR Metrics** using Dlib 68-point facial landmarks  
- **Lighting Condition Detection**  
- **15-second Buffer Logic** to avoid false detections  
- **Session Report** showing attentive vs non-attentive time  
- **Dataset Augmentation** for improved model robustness  

---

## 🚀 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Dlib**
- **Scikit-learn**
- **NumPy / Pandas**
- **Matplotlib**
