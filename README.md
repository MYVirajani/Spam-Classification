# 📧 SMS Spam Classification

This project is a **Spam Classification** application built using **Python**, **NLTK**, and **Scikit-learn**.  
It uses the **SMS Spam Collection Dataset** from Kaggle to train a **Naive Bayes Classifier** that can predict whether an incoming SMS is **Spam** or **Ham (Not Spam)**.

---

## 📂 Dataset
The dataset used in this project is from Kaggle:  
[SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

- **Total entries**: 5,572
- **Classes**:  
  - `ham` → Non-spam messages  
  - `spam` → Spam messages

---

## ⚙️ Features
- Data cleaning & preprocessing (lowercasing, stopword removal, stemming)
- Feature extraction using **TF-IDF Vectorizer**
- Model training using **Multinomial Naive Bayes**
- High accuracy (~97%) on the test set
- Model persistence using `joblib` for later predictions

---
