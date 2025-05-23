# Email-Spam-Classifier

This project builds an **Email Spam Classifier** using Neural Network-based vectorization (NNP) for text representation and a Naïve Bayes model for efficient spam detection, ensuring accurate email classification.

---

## 📖 Project Overview
```
Email-Spam-Classifier/
│
├── data/ # Raw and preprocessed dataset (spam/ham emails)
│ ├── spam.csv
│ └── ham.csv
│
├── notebooks/ # Jupyter notebooks for EDA, model training and testing
│ └── Email_Spam_Model.ipynb
│
├── model/ # Saved trained model files (.pkl or .h5)
│ └── spam_classifier.pkl
│
├── vectorizer/ # Saved vectorizer (NNP or TF-IDF)
│ └── vectorizer.pkl
│
├── train_model.py # Script for preprocessing and model training
├── predict.py # Script to test model on new email text
├── app.py # Streamlit/Flask app for web deployment
├── requirements.txt # Required Python libraries
└── README.md # Project documentation
```

---

## 🛠 Features

- Text preprocessing with tokenization, stopword removal, and normalization
- Neural Network-based vectorization (NNP) for rich text embeddings
- Naïve Bayes classifier for spam detection
- Handles real-world email datasets containing both spam and ham emails
- Provides clear prediction outputs with confidence scores
- Easily extendable for deployment as a web app or integration with email services

---

## 📷 Sample Output

Input: "You have won a lottery worth $10,000! Click now to claim."
Prediction: SPAM ✅

Input: "Hi John, can we reschedule our meeting to 3 PM tomorrow?"
Prediction: HAM 📩

---

## 📌Future Work
  - Deploy the model to cloud platforms such as Heroku or Vercel for web access
  - Enhance text embeddings using BERT or LSTM models for better contextual understanding
  - Incorporate email metadata analysis (subject line, sender info) for improved accuracy
  - Integrate with Gmail or Outlook API for real-time spam filtering and automation

---

## 💡 Technologies Used
  - Python 🐍
  - Scikit-learn 🤖 — Naïve Bayes classification
  - NLTK / SpaCy 🧠 — Text preprocessing and tokenization
  - Pandas & NumPy 📊 — Data manipulation and analysis
  - Streamlit / Flask 🌐 — Web app deployment and user interface
  - Neural Network-based Embeddings (NNP) — Vector representation of email text

---
