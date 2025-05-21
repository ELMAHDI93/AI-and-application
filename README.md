# 📊 Sentiment Analysis of Apple iPhone Customer Reviews

## 📌 Project Info

- **Author:** El Mahdi El Alj (GH1033521)  
- **Course:** Big Data Analytics (M508)  
- **Assignment:** Final Individual Assignment  

---

## 📈 Business Problem

Apple iPhones are among the most popular smartphones worldwide. With rising competition, understanding customer satisfaction is critical. This project employs **sentiment analysis** to automatically classify reviews into:

- Positive  
- Neutral  
- Negative  

This insight can help:
- Improve customer satisfaction
- Understand preferences and pain points
- Guide product improvement strategies

---

## 🎯 Objective

To demonstrate the application of an **NLP pipeline** for sentiment classification using both traditional and advanced models.

---

## 🧠 Methods Used

- Data Cleaning & Preprocessing
- Text Vectorization (TF-IDF)
- Oversampling (SMOTE)
- Machine Learning Models:
  - Logistic Regression
  - Random Forest
  - DistilRoBERTa (Transformer)

---

## 🧰 Libraries and Tools

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `sklearn` (Logistic Regression, Random Forest, metrics)
- `nltk` (Tokenization, Stopwords, Lemmatization)
- `imblearn` (SMOTE for balancing)
- `transformers` (DistilRoBERTa model)
- `datasets`, `torch`

---

## 📁 Dataset

- Source: [Kaggle - iPhone Customer Reviews NLP](https://www.kaggle.com/datasets/mrmars1010/iphone-customer-reviews-nlp/data)
- File used: `iphone.csv`
- Key fields:
  - `reviewDescription`
  - `ratingScore` (used to derive sentiment labels)

---

## ⚙️ Project Workflow

1. **Data Loading & Exploration**
2. **Sentiment Mapping** (based on rating)
3. **Data Cleaning**
   - Lowercase
   - Remove punctuation & non-alpha
   - Tokenization
   - Stopword removal
   - Lemmatization
4. **Feature Engineering**
   - TF-IDF Vector
