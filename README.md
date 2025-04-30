# 🫀 Heart Attack Prediction: Classifier Comparison

This project evaluates multiple machine learning classification algorithms to predict heart attacks based on patient data. The goal is to determine which classifier provides the highest accuracy.

## 📌 Objective

To compare the performance of the following classification models:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**

## 📁 Files

- `HeartAttak.ipynb`: Jupyter notebook containing data processing, model training, and accuracy comparison.
- `heart.csv`: Dataset (must be available in your Google Drive or working directory).

## 📊 Dataset Overview

The dataset includes the following features:

- **Age**: Age of the individual
- **Sex**: Gender (0 = female, 1 = male)
- **Exang**: Exercise-induced angina (1 = yes, 0 = no)
- **Ca**: Number of major vessels (0 to 3)
- **Cp (Chest Pain Type)**:
  - 1: Typical angina (direct heart-related pain)
  - 2: Atypical angina (indirect pain perceived in the heart)
  - 3: Non-anginal pain
  - 4: Asymptomatic
- **Trtbps**: Resting blood pressure
- **Chol**: Serum cholesterol level
- **Fbs**: Fasting blood sugar (1 = high / diabetic, 0 = normal)
- **Rest_ecg**: Resting electrocardiographic results
  - 0: Normal
  - 1: ST abnormality
  - 2: Possible or definite left ventricular hypertrophy
- **Thalach**: Maximum heart rate achieved
- **Target**: Risk of heart attack (0 = low, 1 = high)

## 🚀 How to Run

1. Clone this repo.
2. Upload `heart.csv` to your working directory (or modify the file path in the notebook).
3. Open `HeartAttak.ipynb` using Google Colab or Jupyter.
4. Run all cells to preprocess the data, train models, and evaluate accuracy.

## 🛠 Requirements

For local execution, install these packages:

📄 License
This project is licensed under the MIT License.
You can also find the data set in kaggle
