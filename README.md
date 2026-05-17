# Email-Spam-Detection-with-NLP-and-Machine-Learning
# 📬 Email Spam Classifier (NLP + Machine Learning)

A machine learning project that classifies email messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing techniques.

---

## 🚀 Project Overview

This project builds a text classification model that automatically detects whether an email message is spam or not. It uses classic NLP techniques to convert text into numerical features and machine learning models to make predictions.

---

## 🎯 Objective

To accurately classify email messages into:
- 📩 Ham (legitimate email)
- 🚫 Spam (unwanted or suspicious email)

---

## 🧠 What This Project Covers

- Text preprocessing and cleaning
- Feature extraction using TF-IDF 
- Train-test splitting
- Supervised learning models
- Model evaluation and accuracy measurement
- Handling real-world text data

---

## 📊 Dataset

The dataset contains labeled email messages:
- `text`: the email content
- `spam`: target label (1 = spam, 0 = ham)

---

## ⚙️ Machine Learning Pipeline

1. Load dataset using Pandas  
2. Explore and clean the data  
3. Split data into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train classification model  
6. Evaluate performance using accuracy  

---

## 🤖 Models Used

- Logistic Regression  
- Linear Support Vector Machine (SVM)

---

## 📈 Results

- Achieved accuracy: ~97%–99% (depending on model and vectorization method)
- Strong performance due to clear text patterns in spam messages
