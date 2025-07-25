# 🩺 Multiple Disease Prediction Web App

This repository contains the codebase for an interactive **Multiple Disease Prediction** web application built using **Streamlit**. The application allows users to predict the likelihood of **Heart Disease** and **Diabetes** by inputting relevant health and lifestyle parameters.

## 🚀 Features

- **🫀 Heart Disease Prediction**
  - Predicts the risk of heart disease based on clinical indicators such as age, cholesterol, resting blood pressure, etc.

- **🩸 Diabetes Prediction**
  - Estimates the likelihood of diabetes using parameters like glucose levels, BMI, age, and more.

- **🧑‍💻 Streamlit Web Interface**
  - Clean and user-friendly interface for real-time predictions.

- **📊 Model Training Transparency**
  - Jupyter notebooks with full machine learning pipelines (EDA, preprocessing, training, evaluation).

- **📁 Datasets Included**
  - Datasets used for training and testing the models are available in the repository.

---

## 📂 Project Structure

├── app.py # Streamlit app main file
├── diabetes_model.pkl # Trained Diabetes model
├── heart_model.pkl # Trained Heart Disease model
├── data/
│ ├── diabetes.csv # Dataset for diabetes
│ └── heart.csv # Dataset for heart disease
├── notebooks/
│ ├── diabetes_training.ipynb# Model training notebook for diabetes
│ └── heart_training.ipynb # Model training notebook for heart
├── requirements.txt # Dependencies list
└── README.md # Project documentation

## 🧠 Model Overview
Algorithms Used: Logistic Regression, Random Forest, etc.

Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix

The models were trained using publicly available datasets and evaluated for performance. The notebooks are included for full transparency and reproducibility.
