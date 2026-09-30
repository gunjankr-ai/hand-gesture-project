# 🤖 Hand Gesture Recognition using Teachable Machine

A real-time **Hand Gesture Recognition** web application built using **Google Teachable Machine, TensorFlow.js, JavaScript, HTML5, CSS3, and Webcam**.

The application uses a custom-trained image classification model to recognize different hand gestures through the user's webcam.

---

## 🚀 Project Overview

This project demonstrates how Machine Learning can be integrated into a web application without building a deep learning model completely from scratch.

I used **Google Teachable Machine** to collect training images and train a custom image classification model. The trained model was then exported as a **TensorFlow.js model** and integrated into a web application.

The application captures live webcam frames and predicts the hand gesture in real time.

---

## ✨ Features

- 📷 Real-time webcam input
- 🤖 AI-based hand gesture recognition
- ⚡ Real-time prediction using TensorFlow.js
- 🎯 Custom-trained Machine Learning model
- 🌐 Runs directly in a web browser
- 📊 Displays prediction confidence
- 💻 Simple and responsive user interface

---

## 🖐️ Supported Gestures

The current model recognizes four hand gestures:

| Gesture | Description |
|--------|-------------|
| 👍 Thumbs Up | Positive / Like |
| ✋ Open Hand | Stop / Open Palm |
| ✌️ Victory | Victory / Peace |
| 👌 OK Gesture | OK / Confirm |

---

## 🛠️ Technologies Used

- **Google Teachable Machine** – Model training
- **TensorFlow.js** – Running the ML model in the browser
- **JavaScript** – Application logic
- **HTML5** – Webpage structure
- **CSS3** – User interface styling
- **Webcam** – Real-time image input

---

## 🔄 How It Works

```text
Webcam
   ↓
Capture Hand Image
   ↓
Pre-trained ML Model
   ↓
Image Classification
   ↓
Gesture Prediction
   ↓
Display Result