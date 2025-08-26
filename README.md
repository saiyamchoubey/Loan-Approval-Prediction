# 🏦 Loan Approval Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) 
![Flask](https://img.shields.io/badge/Flask-2.0+-black?logo=flask) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn) 
![Status](https://img.shields.io/badge/Status-Active-success?style=flat)

---

## 📑 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Contribution](#contribution)

---

## 📌 Introduction
**Loan Approval Prediction** is a user-friendly **web application** that uses **machine learning models** to predict whether a loan application will be **approved ✅ or rejected ❌**.  

With a clean and intuitive UI, users can input details such as income, loan amount, credit history, and instantly receive a prediction.  

This project demonstrates an **end-to-end pipeline**:  
📊 Data preprocessing → 🤖 Model training → 🌐 Deployment with Flask.

---

## 🎥 Demo
### 🔗 Live Application
👉 [Click here to try the app](https://loan-approval-prediction-b5l5.onrender.com/)  

### 📺 Video Demo
![Loan Approval Prediction Demo](https://github.com/neerajcodes888/Loan-Approval-Prediction/assets/98253646/276b7691-55f1-4aa4-95cb-daf5e76c3ffa)

---

## 🔄 Project Workflow
```mermaid
flowchart TD
    A[User Inputs Data] --> B[Flask Web Form]
    B --> C[Preprocessing: Cleaning, Encoding, Scaling]
    C --> D[ML Model: Logistic Regression / Random Forest / XGBoost]
    D --> E[Prediction: Approved / Rejected]
    E --> F[Result Displayed in UI]
```
---

## ⚙️ Installation

### 1. Install dependencies
```bash
pip install -r requirements.txt
```
### 2. Run the Flask app
```bash
python app.py
```
---

## 🚀 Usage

1. Open your browser → [http://127.0.0.1:5000/](http://127.0.0.1:5000/)  
2. Fill in applicant details.  
3. Submit → get instant loan approval prediction.  

---

## ✨ Features

- 📊 Predicts loan approval using trained ML models.  
- 🎨 Modern UI built with HTML5 + Tailwind CSS.
- ⚡ Fast and accurate predictions.
- 🔄 End-to-end pipeline: Preprocessing → Model → Deployment.

---

## 🛠 Tech Stack

- **Language**: Python
- **Frameworks**: Flask, scikit-learn 
- **Frontend**: HTML5, Tailwind CSS
- **Deployment**: Flask (local), extensible for Docker/Cloud (Azure/Heroku)

---

## 🔮 Future Enhancements

- 📌 Add explainability (SHAP/LIME) to show why an application is approved/rejected.
- 📌 Dockerize and deploy with Azure DevOps CI/CD pipeline.  
- 📌 Improve accuracy using ensemble learning + hyperparameter tuning.
- 📌 Upgrade UI with React or Angular.









