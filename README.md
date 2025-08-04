# 🔐 Network Intrusion Detection System (NIDS) using Machine Learning

This project focuses on developing a Machine Learning-based **Network Intrusion Detection System (NIDS)** that can detect and classify various types of cyber-attacks like DoS, Probe, R2L, and U2R using the Kaggle intrusion detection dataset. The system is trained, evaluated, and deployed on **IBM Cloud Lite**, making it scalable, secure, and easy to access.

---

## 📌 Problem Statement

With the rise of digital networks and increasing cyber threats, traditional intrusion detection systems that rely on static rules or signature-based detection are no longer sufficient. These systems often fail to detect new or evolving attacks.

**The goal of this project is to build an intelligent and automated NIDS using machine learning that can accurately analyze network traffic and detect malicious activities in real-time.**

---

## 📊 Dataset

- **Source**: [Kaggle Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
- **Contents**: Network connection logs with various features including:
  - Duration, protocol type, service, source bytes, destination bytes
  - Flag values, connection status
  - Attack type label (Normal, DoS, Probe, R2L, U2R)

---

## 🧪 Technologies Used

- **Python**: pandas, scikit-learn, xgboost, seaborn, matplotlib
- **IBM Cloud Lite**:
  - IBM Watson Studio
  - IBM Cloud Object Storage
  - IBM Watson Machine Learning
  - (Optional) IBM Cloud Functions or App Services

---

## 🚀 Model Development

### ✅ Algorithms Used
- **Snap Decision Tree**
- **XGBoost**
- **Logistic Regression** (baseline model)

### 📊 Evaluation Metrics
- **Accuracy**
- **F1-Score**
- **Confusion Matrix**
- **Precision & Recall**

---

## ☁️ Deployment on IBM Cloud Lite

- **IBM Watson Studio**: Used to develop and train machine learning models in a notebook environment.
- **IBM Cloud Object Storage**: Stores the dataset and model files securely.
- **IBM Watson Machine Learning**: Hosts the trained model and exposes it as a REST API for real-time predictions.
- **IBM Cloud Functions (Optional)**: Automates model predictions when new network logs are uploaded.
- **User Interface (Optional)**: A simple web app or dashboard to submit input features and visualize prediction results.

---

