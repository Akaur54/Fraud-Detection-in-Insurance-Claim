# 🕵️‍♂️ Fraud Detection in Insurance Claims

## 📌 Overview
Insurance fraud is a major challenge in the industry, leading to substantial financial losses. This project applies **Machine Learning** techniques to detect fraudulent claims with high accuracy. By analyzing patterns in historical claim data, our model predicts the likelihood of fraud, helping insurance companies minimize risks.

## 🔍 Problem Statement
Fraudulent claims cost insurance companies billions every year. Traditional rule-based fraud detection methods are **inefficient and prone to false positives**. Machine Learning provides a **data-driven approach** to identify fraudulent activities with better precision.

## 🎯 Objective
- **Build a Machine Learning model** that accurately classifies insurance claims as **fraudulent or legitimate**.
- Compare multiple ML algorithms and select the most effective one.
- Improve fraud detection while **minimizing false positives**.

## 🛠️ Methodology
### **1️⃣ Data Preprocessing**
- Clean and preprocess raw insurance claim data.
- Feature selection and engineering to improve model accuracy.

### **2️⃣ Model Selection & Training**
We experimented with **multiple ML models** and evaluated their performance based on **AUC (Area Under the Curve)** scores:
- **KNN (AUC = 0.59) 🟥**
- **SVC (AUC = 0.61) 🟦**
- **Random Forest (AUC = 0.64) 🟪 (Best Model ✅)**
- **Decision Tree (AUC = 0.57) ⚫**

### **3️⃣ Fraud Detection & Prediction**
- Trained models to detect fraudulent claims.
- **Random Forest achieved the highest accuracy (AUC = 0.64)**.
- Deployed the model for real-time fraud detection.

## 📷 Model Performance
![image](https://github.com/user-attachments/assets/745ed9f7-9cc5-4749-8e24-1d71dfda5c9d)


## 🖥️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Scikit-learn)
- **Machine Learning Models:** KNN, SVC, Random Forest, Decision Tree
- **Jupyter Notebook** for experimentation
- **Flask** (for API integration)

## ✅ Results
- **Random Forest outperformed other models with an AUC of 0.64.**
- **Improved fraud detection accuracy, reducing false claims.**
- **Provided a scalable solution for insurance companies.**

## 🚀 Future Improvements
- Fine-tune the **Random Forest model** for better precision.
- Use **deep learning models (e.g., Neural Networks) for enhanced performance**.
- Deploy the model as a **real-time fraud detection API**.


---
💡 **Preventing Fraud with Smart AI Solutions!** 🚀
