# 😊 Emotion Detection Using Deep Learning

A Deep Learning-based Facial Emotion Recognition system that classifies human emotions from facial expressions using Convolutional Neural Networks (CNNs). The model is trained on the FER-2013 dataset and can detect emotions in real-time using a webcam feed.

---

## 📖 Project Overview

This project uses Deep Learning and Computer Vision techniques to identify human emotions from facial images. The system detects faces using OpenCV's Haar Cascade classifier and predicts one of seven emotions using a trained CNN model.

The model is trained on the FER-2013 dataset, which contains grayscale facial images categorized into different emotional states.

---

## 🎯 Objectives

* Detect human faces in real-time
* Classify facial expressions into emotions
* Apply Deep Learning techniques for image classification
* Demonstrate Computer Vision applications using Python
* Build an intelligent emotion recognition system

---

## 🚀 Features

* Real-time Emotion Detection
* Facial Expression Recognition
* CNN-based Deep Learning Model
* Webcam Integration
* Face Detection using Haar Cascades
* Seven Emotion Classification
* Pre-trained Model Support

---

## 😃 Supported Emotions

The model classifies facial expressions into the following categories:

* Angry 😠
* Disgust 🤢
* Fear 😨
* Happy 😀
* Neutral 😐
* Sad 😢
* Surprise 😲

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras

### Computer Vision

* OpenCV

### Data Processing

* NumPy

### Dataset

* FER-2013 Dataset

### Development Tools

* Jupyter Notebook / Python IDE
* Git
* GitHub

---

## 📂 Project Structure

```text
Emotion-Detection/
│
├── src/
│   ├── emotions.py
│   ├── dataset_prepare.py
│   ├── haarcascade_frontalface_default.xml
│
├── imgs/
│   └── accuracy.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Required Libraries

* TensorFlow
* OpenCV
* NumPy

---

## 📊 Dataset

The project uses the FER-2013 (Facial Expression Recognition) dataset.

Dataset Characteristics:

* 35,887 grayscale images
* Image size: 48 × 48 pixels
* 7 emotion categories

---

## ▶️ Running the Project

### Train the Model

```bash
cd src
python emotions.py --mode train
```

### Run Emotion Detection

```bash
cd src
python emotions.py --mode display
```

The webcam will start, and the system will detect faces and predict emotions in real time.

---

## 🧠 Model Workflow

1. Capture image from webcam
2. Detect face using Haar Cascade
3. Preprocess image
4. Resize to 48×48 pixels
5. Pass image to CNN model
6. Predict emotion
7. Display detected emotion

---

## 📈 Results

* Real-time emotion recognition
* CNN-based classification
* FER-2013 trained model
* Achieved effective emotion prediction across seven classes

---

## 📸 Output

Add screenshots here:

* Emotion Detection Window
* Happy Emotion Prediction
* Sad Emotion Prediction
* Accuracy Graph

---

## 🔮 Future Enhancements

* Higher Accuracy Models
* Transfer Learning (ResNet, EfficientNet)
* Multi-face Emotion Detection
* Video Emotion Analytics
* Mobile Application Deployment
* Emotion-based Recommendation Systems
* Cloud Deployment

---

## 🎓 Learning Outcomes

* Deep Learning Fundamentals
* Convolutional Neural Networks (CNNs)
* Computer Vision
* OpenCV Face Detection
* TensorFlow & Keras
* Image Classification
* Model Training & Evaluation

---

## 👨‍💻 Author

Parth Biradar

B.Tech Computer Science & Engineering (Data Science)

---

