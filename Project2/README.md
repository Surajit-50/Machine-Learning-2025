# 🫀 Heart Disease Prediction using Machine Learning

## 📌 Objective
The goal of this project is to develop a machine learning model that can predict the likelihood of cardiovascular disease using patient data from the Framingham Heart Study.

---

## 📊 Dataset Overview
- **Source:** Framingham Heart Study
- **Features:** Age, gender, blood pressure, cholesterol, BMI, smoking habits, diabetes, etc.
- **Target Variable:** `TenYearCHD` (1 = high risk of heart disease in 10 years, 0 = low risk)

---

## 🔍 Exploratory Data Analysis (EDA)
- Checked class distribution of the target
- Explored feature distributions using histograms
- Analyzed correlation between variables
- Identified key indicators affecting heart disease risk

---

## 🛠 Data Preprocessing
- Renamed confusing columns
- Handled missing values (removed or imputed as needed)
- Scaled numerical features for model compatibility

---

## 🤖 Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)

Each model was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## ✅ Results
- **Best Model:** SVC  
- **Accuracy:** 83.5%
- **Top Influencing Features:** Age, cholesterol levels, blood pressure, smoking status

---

## 🔮 Future Work
- Implement Neural Networks with TensorFlow/Keras
- Perform hyperparameter tuning for better accuracy
- Deploy the model using a web framework like Django or Flask

---

## 📁 Project Structure
📦 Heart Disease Prediction ├── 📄 p1.ipynb # Main Jupyter Notebook ├── 📄 README.md # Project overview

> ⚠️ This project is for educational purposes only and should not be used for medical decision-making.

