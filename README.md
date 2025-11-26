# m1-dataviz-sentiment-analysis

**French Twitter Sentiment Analysis Project (NLP)**  

This project focuses on analyzing the **sentiment of tweets in French** to classify them as **positive, negative, or neutral**, using Natural Language Processing and machine learning techniques.

---

## 📝 Overview
The goal of this project is to demonstrate **text preprocessing, feature extraction, and model building** for sentiment classification on social media data. It also highlights the use of **SpaCy pipelines** and evaluation metrics such as **F1-score**.

---

## 🔹 Data
- Source: **Twitter** (tweets in French)  
- Size: X tweets (replace with actual number if available)  
- Data preprocessing includes:  
  - Cleaning text (removing punctuation, links, mentions, emojis)  
  - Removing stopwords  
  - Tokenization and lemmatization using **SpaCy**  

---

## 🔹 Methodology
1. **Text Preprocessing:**  
   - Standard cleaning and normalization  
   - Stopwords removal  
   - SpaCy pipeline for tokenization and lemmatization  

2. **Embedding:**  
   - TF-IDF 

3. **Modeling:**  
   - Tested several classifiers including:  
     - Bernoulli Naive Bayes 
     - **Logistic Regression**  
     - SVC
   - Hyperparameter tuning for optimal performance  

---

## 📊 Results
- **Best F1-score:** 0.80 with **Logistic Regression Regularized**  
- Metrics evaluated: **Precision, Recall, F1-score**  
- Visualizations include **sentiment distribution** and **confusion matrix**  

---

## 🛠️ Tools & Technologies
- **Python**  
- **Pandas, NumPy** for data manipulation  
- **Scikit-learn** for machine learning  
- **SpaCy** for NLP  
- **Matplotlib / Seaborn** for visualization  
