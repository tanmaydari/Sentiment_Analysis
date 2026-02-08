# Twitter Sentiment Analysis using NLP

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : TANMAY DARI

*INTERN ID* : CTIS2656

*DOMAIN* : DATA ANALYTICS

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH KUMAR

## Project Overview
This project performs Sentiment Analysis on Twitter data using Natural Language Processing (NLP) techniques. The goal is to classify tweets as Positive or Negative based on their content.

---

## Dataset
- Source: Sentiment140 (Twitter dataset)
- Total records: 1.6 million tweets
- Used sample: 100,000 tweets (for faster processing)
- Labels:
  - 0 = Negative
  - 1 = Positive

---

## Technologies Used
- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- Matplotlib, Seaborn
- WordCloud

---

## Project Workflow

### 1. Data Preprocessing
- Converted text to lowercase
- Removed URLs, mentions, punctuation
- Stopword removal
- Stemming

### 2. Feature Extraction
- TF-IDF Vectorization
- Unigrams and Bigrams

### 3. Model Building
- Logistic Regression
- Multinomial Naive Bayes

### 4. Model Performance
- Logistic Regression Accuracy: ~76%
- Naive Bayes Accuracy: ~75%

Moderate accuracy is expected due to noisy and informal nature of Twitter data.

---

## Visualizations
- Confusion Matrix
- WordCloud for Positive and Negative Tweets

---

## Applications
- Social media sentiment monitoring
- Customer feedback analysis
- Brand reputation tracking

---

## Project Structure

Google Colab Link: <https://colab.research.google.com/drive/1vOee3S1-WhT5GRFtPItVYY7sdjnnY1TJ?usp=sharing>
