#  SMS Spam Classifier

A simple machine learning project that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) and a Multinomial Naive Bayes model.

---

## 🔍 Features

- Preprocessing: lowercasing, punctuation removal, stopword removal, stemming
- TF-IDF vectorization
- Multinomial Naive Bayes classifier
- Model and vectorizer saved as `.pkl` files
- Deployed using Streamlit (if applicable)

---

## 🧪 Demo

You can test the model by loading `model.pkl` and `vectorizer.pkl` in a Streamlit or Python interface.

---

## 📁 Files

- `spam_classifier.ipynb` – Jupyter Notebook with training code
- `app.py` –  Streamlit app for the interface
- `vectorizer.pkl` – TF-IDF vectorizer
- `model.pkl` – Trained ML model

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sushanthum616/sms-spam-classifier.git
   cd sms-spam-classifier
