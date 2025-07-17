# 📧 Spam Detection Using NLP & Machine Learning

## 📌 Project Overview
This project focuses on building a **text classification model** to detect whether an email/message is **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and **Machine Learning**.  
Email spam is one of the most common problems in digital communication, and detecting spam accurately is crucial for security and user experience.

---

## ✅ Problem Statement
Given a dataset of email/text messages labeled as **spam** or **ham**, the goal is to **train a model that can classify unseen messages accurately**.

---

## 🛠 Steps Taken:
### 1️⃣ **Data Collection**
- Used a publicly available dataset containing labeled email messages.

### 2️⃣ **Data Cleaning & Preprocessing**
- Removed unwanted characters, punctuation, and stopwords.
- Converted text to lowercase for normalization.
- Tokenization and Lemmatization applied.

### 3️⃣ **Feature Extraction**
- Converted text data into numerical format using:
  - **TF-IDF Vectorization**
  - **Bag of Words (BoW)**

### 4️⃣ **Model Building**
- Implemented multiple machine learning algorithms:
  - **Naive Bayes**
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
- Evaluated models using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**

### 5️⃣ **Model Evaluation**
- Plotted **Confusion Matrix** and calculated performance metrics.

---

## 📈 Key Insights:
✔ **Naive Bayes performed best** for text classification in this case.  
✔ TF-IDF significantly improves accuracy compared to simple Bag of Words.  

---

## 🛠 Tools & Technologies:
- **Python**
- **Libraries**: `Pandas`, `NumPy`, `Scikit-learn`, `NLTK`
- **Jupyter Notebook** for development.

---

