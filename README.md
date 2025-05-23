# Email-Spam-Classifier

This project builds an **Email Spam Classifier** using Neural Network-based vectorization (NNP) for text representation and a Naïve Bayes model for efficient spam detection, ensuring accurate email classification.

---

## 📖 Project Overview

Email spam filtering is essential to protect users from unwanted and potentially harmful emails. This project leverages advanced text representation techniques using Neural Network-based embeddings (NNP) combined with a classic Naïve Bayes classifier to detect spam emails effectively. The model classifies incoming emails as either **SPAM** or **HAM** (non-spam).

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

```vbnet
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
