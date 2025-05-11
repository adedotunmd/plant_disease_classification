# Tomato Leaf Disease Classification using Image Processing and Machine Learning

## 📘 Project Overview

This project explores the application of image processing and machine learning techniques for the automated classification of tomato leaf diseases. The study aims to assist farmers and agricultural practitioners by providing a reliable, fast, and accurate tool for disease detection, ultimately improving crop yield and food security.

The case study uses a publicly available dataset from Kaggle, comprising tomato leaf images affected by various diseases as well as healthy samples. The project compares the effectiveness of classical machine learning models and deep learning architectures, including CNNs.

---

## 👨‍🔬 Authors

- Adedotun Adedamola Ayodele  
- Segun Samuel Otitolaye  
- Babasoji Morayo Arije  
- Antonia Chinazor Ezulike  
- Nnenna Agbeze Oko

Rome Business School — Master in Data Science Management  
Academic Year: 2023/2024  
Project defended: September 14, 2024

---

## 🧠 Objectives

- Build a system for automatic classification of tomato leaf diseases.
- Compare the performance of different ML models.
- Improve explainability and trust in AI-based crop disease tools.

---

## 🧪 Methodology

- **Data Source**: Tomato leaf dataset from Kaggle (10,000+ images, 10 classes)
- **Preprocessing**: Resizing, normalization, augmentation
- **Classical ML Models**:  
  - Support Vector Machine (SVM)  
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
  - K-Nearest Neighbors (KNN)
- **Deep Learning Model**:  
  - Custom CNN  
  - Transfer Learning (e.g., VGG16, ResNet50)

---

## 📊 Results Summary

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| SVC              | 92%      | 90%       | 95%    | 92.5%    |
| KNN              | 87%      | 98%       | 99%    | 98.0%    |
| Logistic Regression | 83%   | 98%       | 98%    | 98.0%    |
| Random Forest    | 90%      | 97%       | 99%    | 98.0%    |
| Decision Tree    | 88%      | 98%       | 97%    | -        |

🔍 *Best Overall Model*: KNN and Random Forest (high F1-score and Recall)  
✅ *Best Accuracy*: Support Vector Classifier (SVC)

---

## 📦 Technologies Used

- Python
- Scikit-learn
- TensorFlow / Keras
- OpenCV
- Matplotlib / Seaborn



