# Restaurant Review Sentiment Analysis

📊 Natural Language Processing (NLP) | Text Classification | Machine Learning

---

## 📌 Project Overview

This project focuses on performing sentiment analysis on restaurant reviews using Natural Language Processing (NLP) techniques. The objective is to classify customer reviews as **Positive (1)** or **Negative (0)** based on textual content.

The solution applies text preprocessing, Bag-of-Words feature extraction, and multiple machine learning classifiers to evaluate sentiment prediction performance.

---

## 🎯 Objective

The primary goals of this project were:

- Clean and preprocess raw text data
- Convert textual reviews into numerical representations
- Train classification models for sentiment prediction
- Compare performance of different algorithms

---

## 📊 Dataset Description

The dataset consists of:

- **1000 restaurant reviews**
- A review text column
- A binary target column indicating sentiment:
  - `1` → Positive Review
  - `0` → Negative Review

---

## 🧹 Text Preprocessing

The following preprocessing steps were performed:

- Removal of non-alphabetic characters
- Conversion to lowercase
- Tokenization
- Stopword removal (NLTK)
- Stemming using Porter Stemmer

This process transformed raw reviews into cleaned textual data suitable for modeling.

---

## 🔤 Feature Extraction

Used **Bag-of-Words (CountVectorizer)** to convert text into numerical feature vectors:

- Maximum features: 1500
- Created sparse matrix representation of word frequencies

---

## 🤖 Models Implemented

Three classification algorithms were trained and evaluated:

### 1️⃣ Multinomial Naive Bayes
- Suitable for discrete word frequency features
- Fast and efficient baseline model

### 2️⃣ Bernoulli Naive Bayes
- Designed for binary feature vectors

### 3️⃣ Logistic Regression
- Linear classification model
- Generally performs well in text classification tasks

---

## 📈 Model Evaluation

Models were evaluated using:

- Confusion Matrix
- Accuracy
- Precision
- Recall

These metrics were computed on a 70/30 train-test split.

---


## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- CountVectorizer
- Naive Bayes
- Logistic Regression

---

---

## 🚀 Conclusion

This project demonstrates a foundational NLP pipeline including:

- Text cleaning
- Feature extraction
- Model comparison
- Performance evaluation

It serves as a practical introduction to sentiment analysis using machine learning techniques.

---

## 👤 Author

Swaroop Sandanshive


