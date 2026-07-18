# Neonatal-jaundice-detection

A machine learning-based system designed to assist in the detection of neonatal jaundice using image processing and deep learning techniques. The project explores computer vision approaches to analyze infant images and classify jaundice conditions.

## 📌 Project Overview

Neonatal jaundice is a common condition in newborns caused by increased bilirubin levels. Early detection is important to prevent possible health complications.

This project aims to develop an automated detection system using image-processing techniques and machine learning models to identify jaundice patterns from images.

The system combines traditional machine learning and deep learning approaches to evaluate performance and improve detection accuracy.

## 🚀 Features

* Image-based neonatal jaundice detection
* Image preprocessing and feature extraction
* Machine learning-based classification
* Deep learning model implementation
* User-friendly frontend interface for prediction
* Model comparison and evaluation

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning & Deep Learning

* Scikit-learn
* TensorFlow / Keras
* HOG (Histogram of Oriented Gradients)
* Support Vector Machine (SVM)
* MobileNetV2

### Image Processing

* OpenCV
* NumPy
* Matplotlib

### Development Tools

* Jupyter Notebook
* Git & GitHub

## 🧠 Models Implemented

### 1. HOG + SVM Model

* Extracted image features using Histogram of Oriented Gradients (HOG)
* Classified images using Support Vector Machine (SVM)

### 2. MobileNetV2 Model

* Implemented transfer learning using MobileNetV2
* Fine-tuned the model for neonatal jaundice detection

## 📊 Results

The developed system achieved:

**Accuracy: 96.46%**

The performance was evaluated using metrics such as:

* Accuracy
* Confusion Matrix
* ROC Curve
* Classification performance analysis

## 📂 Project Structure

```
Neonatal-jaundice-detection/
│
├── Myproject.ipynb
│
├── models/
│   ├── mobilenetv2_model.h5
│   └── svm_model.pkl
│
├── screenshots/
│   ├── home_page.png
│   └── prediction_result.png
│
├── requirements.txt
│
└── README.md
```




## ⚙️ Installation & Usage

### Clone the repository

```bash
git clone https://github.com/Mani010903/Neonatal-jaundice-detection.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

Open the Jupyter Notebook:

```bash
jupyter notebook Myproject.ipynb
```

Follow the notebook steps to preprocess images, load the trained models, and perform predictions.

## 📚 Future Improvements

* Improve dataset diversity for better generalization
* Deploy the model as a web application
* Optimize the model for real-time detection
* Integrate additional medical parameters for improved analysis

## 👨‍💻 Author

**Mani Gupta**

Computer Science Graduate | Machine Learning & Cloud Enthusiast

LinkedIn:linkedin.com/in/mani-gupta-088a702b5

GitHub: https://github.com/Mani010903
