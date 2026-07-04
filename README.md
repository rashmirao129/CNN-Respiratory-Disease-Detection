# CNN-Respiratory-Disease-Detection
Machine Learning project to detect and classify respiratory diseases using Convolutional Neural Networks (CNN) built with Python. Uses deep learning techniques for medical data processing and disease pattern recognition.
## 🫁 Respiratory Disease Detection using CNN
### 📌 Overview
A Machine Learning project to detect respiratory 
diseases using Convolutional Neural Networks (CNN) 
built with Python. Developed as part of MCA at 
NMAMIT Nitte (2022).
### 🎯 Objective
Automate the detection and classification of 
respiratory diseases from patient data using 
deep learning techniques.
### ✨ Features
- 🧠 Deep learning based disease classification
- 🫁 Respiratory disease pattern recognition
- 📊 CNN architecture for feature extraction
- 🔬 Medical data processing pipeline
- 📈 Disease prediction and classification

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-yellow?style=flat)
![CNN](https://img.shields.io/badge/CNN-red?style=flat)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-green?style=flat)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-purple?style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-orange?style=flat)
[![Keras](https://img.shields.io/badge/Keras-Deep_Learning-red?style=flat&logo=keras)](https://keras.io)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)](https://jupyter.org)
[![Anaconda](https://img.shields.io/badge/Anaconda-Environment-green?style=flat&logo=anaconda)](https://anaconda.org)
![Healthcare AI](https://img.shields.io/badge/Healthcare_AI-blue?style=flat)

---

## 🎯 Problem Statement

Diagnosing respiratory diseases from chest X-rays typically requires expert radiologists — a resource that is scarce and expensive, especially in rural healthcare settings. This project builds a deep learning system to automatically classify chest X-ray images into Pneumonia, COVID-19, or Normal categories, enabling faster and more accessible clinical diagnosis.

### 📊 Dataset
- Source: Kaggle Chest X-Ray Images dataset
- Total: 6,432 images (5,144 training / 1,288 testing)
- Classes: Pneumonia vs Normal

### 🧠 Models Built & Compared
| Model | Accuracy |
|-------|----------|
| Custom CNN (from scratch) | 91.64% |
| VGG16 (Transfer Learning) | 96.31% |
| MobileNet (Transfer Learning) | 98.23% ✅ |

### 🛠️ Tech Stack
- Python 3, Keras, Jupyter Notebook, Anaconda
- Techniques: Data Augmentation, Dropout, Max-Pooling, Transfer Learning
- Evaluation: Confusion Matrix, ROC Curve, Precision/Recall/F1-Score

### 📈 Key Results
- Best accuracy: 98.23% (MobileNet)
- MobileNet recommended for deployment: lightweight (30MB vs VGG16's 500MB), mobile-compatible
### 🏗️ Architecture
- **Language:** Python
- **Model:** Convolutional Neural Network (CNN)
- **Domain:** Healthcare AI / Medical Imaging
### 🎓 Academic Details
- **Institution:** NMAM Institute of Technology, Nitte
- **Degree:** MCA
- **Year:** 2022
