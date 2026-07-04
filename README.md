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
### 🎯 Problem Statement
Diagnosing respiratory diseases from chest X-rays typically requires expert radiologists — a resource that is scarce and expensive, especially in rural healthcare settings. This project builds a deep learning system to automatically classify chest X-ray images into Pneumonia, COVID-19, or Normal categories, enabling faster and more accessible clinical diagnosis.
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

### 📊 Dataset
| Parameter | Details |
|-----------|---------|
| Source | Kaggle — Chest X-Ray Images dataset|
| Total Images | 6,432 chest X-rays |
| Training Set | 5,144 images (80%) |
| Testing Set | 1,288 images (20%) |
| Class Distribution | 74.3% Pneumonia · 25.7% Normal |
| Image Type | PA view frontal chest X-rays |

### 🧠 Models Built & Compared
| Model | Architecture | Epochs | Accuracy |
|-------|-------------|--------|----------|
| Custom CNN | Built from scratch | 12 | 91.64% |
| VGG16 | Transfer Learning (Oxford) | — | 96.31% |
| **MobileNet** | **Transfer Learning (Google)** | **12** | **98.23% ✅** |

**Winner: MobileNet** — highest accuracy AND lightest model (30MB vs VGG16's 500MB), making it suitable for mobile healthcare applications.

### 🏗️ Custom CNN Architecture

```
Input (Chest X-Ray Image)
    ↓
Conv2D (32 filters, 3x3) → ReLU → MaxPooling (2x2)
    ↓
Conv2D (64 filters, 3x3) → ReLU → MaxPooling (2x2)
    ↓
Conv2D (128 filters, 3x3) → ReLU → MaxPooling (2x2)
    ↓
Flatten
    ↓
Dense (64 nodes) → Dropout (0.25)
    ↓
Dense (64 nodes) → Dropout (0.50)
    ↓
Output → Softmax (Normal / Pneumonia / COVID-19)
```
### ⚙️ Methodology
1. **Data Collection** — Downloaded 6,432 labelled chest X-rays from Kaggle
2. **Preprocessing** — Noise removal, resizing, normalization (pixel values 0→1)
3. **Data Augmentation** — Rotation, flipping, cropping, stretching to increase dataset variety
4. **Model Training** — Custom CNN + VGG16 + MobileNet with Adam optimizer
5. **Evaluation** — Confusion matrix, ROC curve, Accuracy/Precision/Recall/F1-score/Sensitivity/Specificity

### 🏗️ Architecture
| Category | Tools |
|----------|-------|
| Language | Python 3 |
| Deep Learning Framework | Keras |
| Environment | Jupyter Notebook, Anaconda |
| Models | Custom Convolutional Neural Network (CNN), VGG16, MobileNet |
| Techniques | Transfer Learning, Data Augmentation, Dropout, Max-Pooling, Adam Optimizer |
| Evaluation | Confusion Matrix, ROC Curve, Precision/Recall/F1-Score |

### 📈 Key Results
- **MobileNet achieved 98.23% accuracy** — best performing model - Best accuracy: 98.23% (MobileNet)
- MobileNet recommended for deployment: lightweight (30MB vs VGG16's 500MB), mobile-compatible
- ROC curve approaching AUC = 1.0 — strong class discrimination
- Confusion Matrix: 300/390 Pneumonia cases correctly identified

### 🏥 Healthcare Relevance
This project directly connects to clinical healthcare IT — the same chest X-ray (DICOM) data analyzed by this model flows through systems like IntelliSpace PACS and Rhapsody that I worked with professionally at Philips Innovation Campus.
- **Language:** Python
- **Model:** Convolutional Neural Network (CNN)
- **Domain:** Healthcare AI / Medical Imaging
### 🎓 Academic Details
- **Institution:** NMAM Institute of Technology, Nitte
- **Degree:** MCA
- **Year:** 2022
### 👩‍💻 Author
**Rashmi Rao** | MCA — NMAMIT, Nitte | Department of MCA
[LinkedIn](https://www.linkedin.com/in/rashmi-rao-1692a023b/) · [GitHub](https://github.com/rashmirao129)
