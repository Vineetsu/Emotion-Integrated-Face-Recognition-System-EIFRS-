# Emotion-Integrated Face Recognition System (EIFRS)

## 🔐 Overview

**EIFRS (Emotion-Integrated Face Recognition System)** is a dual-factor biometric authentication system that combines **facial recognition** with **emotion detection** to provide a more secure and intelligent access control mechanism.

Unlike traditional face recognition systems, EIFRS adds an emotional state check to ensure the user is both physically present and emotionally consistent (e.g., neutral or calm) — minimizing spoofing risks from static images or deepfakes.

---

## 🎯 Key Features

- 🎭 **Facial Recognition** using deep learning-based face embeddings (e.g., FaceNet or OpenCV).
- 😐 **Emotion Detection** via CNN-based classification (e.g., FER2013 or custom emotion dataset).
- 🔐 **Dual-Factor Biometric Authentication**: access is granted only if both identity and expected emotion are matched.
- 📈 **Real-time Webcam Integration** for live detection and validation.
- 📊 **Logging & Session Reports** of access attempts with timestamps and prediction confidence.

---

## 🧠 Use Cases

- 🔒 Secure access to personal devices or vaults
- 👨‍💼 Employee login with emotional readiness check
- 🧠 Behavioral biometrics for healthcare or psychology
- 🎮 Emotion-aware user authentication in gaming or VR

---

## 🛠️ Tech Stack

| Component           | Technology/Library            |
|---------------------|-------------------------------|
| Face Recognition    | OpenCV, dlib, FaceNet, or DeepFace |
| Emotion Detection   | Keras, TensorFlow / PyTorch (CNN) |
| Data Sources        | FER-2013, CK+, or custom images|
| Language            | Python 3.x                     |

---

