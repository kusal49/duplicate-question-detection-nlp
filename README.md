# Duplicate Question Detection using NLP

This project is an end-to-end **Natural Language Processing (NLP) system** that detects whether two questions are semantically duplicate, similar to Quora’s duplicate question detection system.

The model is deployed as a **live web application** using Streamlit and can be accessed by anyone in real-time.

---

## 🚀 Live Demo
👉 https://duplicate-question-detection-nlp-kusal49.streamlit.app  

---

## 📂 GitHub Repository
👉 https://github.com/kusal49/duplicate-question-detection-nlp  

---

## 🧠 Problem Statement
Online Q&A platforms like Quora and StackOverflow contain millions of questions.  
Many users ask the **same question in different ways**, which creates duplicate content.

The goal of this system is to:
> Given two questions, predict whether they mean the same thing.

---

## ⚙️ How the System Works

1. User enters two questions in the web app  
2. Both questions are **preprocessed**  
3. Multiple **linguistic and similarity features** are extracted  
4. A trained **Machine Learning model** predicts whether they are duplicate  

---

## 🧪 Features Used

The model uses a combination of:

- **Text Preprocessing**
  - Lowercasing  
  - Removing HTML  
  - Expanding contractions  
  - Removing punctuation  

- **Statistical Features**
  - Number of common words  
  - Total word count  
  - Token overlap  

- **Fuzzy Matching**
  - Token set ratio  
  - Partial match ratio  
  - Similarity scores  

- **Bag of Words (BoW)**
  - CountVectorizer on both questions  

All features are concatenated and passed into the ML classifier.

---

## 🧰 Tech Stack

- Python  
- NLP (NLTK, BeautifulSoup)  
- Scikit-learn  
- FuzzyWuzzy  
- Distance  
- Streamlit  
- Git & GitHub  
- Cloud Deployment  

---

## 📦 Project Structure

