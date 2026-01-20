# ✈️ Twitter US Airline Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn%20|%20Plotly%20|%20NLTK-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project focuses on transforming **Unstructured Data** (raw tweets) into structured formats for NLP tasks. It analyzes customer sentiment (Positive, Negative, Neutral) regarding US Airlines using various **Natural Language Processing (NLP)** techniques and **Machine Learning**.

The project covers the full pipeline: Data Ingestion → Preprocessing → Feature Engineering → Vectorization (TF-IDF) → Modeling → Interactive Visualization.

## 📂 Dataset
* **Source:** [Twitter US Airline Sentiment Dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
* **Content:** ~14,000 tweets classified as Positive, Negative, or Neutral.

## 🛠️ Key Features & Techniques

### 1. Data Cleaning & Preprocessing
* **Regex:** Extracted metadata features like `has_url`, `has_mention`, and `has_hashtag`.
* **NLTK:** Applied `Tokenization` and `Stopwords Removal` to clean raw text.
* **Text Normalization:** Lowercasing and removing non-alphabetic characters.

### 2. Feature Extraction (Vectorization)
Implemented and compared three different methods:
* ✅ **TF-IDF (Term Frequency-Inverse Document Frequency)** - *Used for the final model.*
* 🔄 **Bag of Words (BoW)**
* 🔢 **One-Hot Encoding**

### 3. Machine Learning Model
* **Algorithm:** Logistic Regression.
* **Goal:** Multi-class classification (Positive vs. Negative vs. Neutral).
* **Metrics:** Accuracy, Confusion Matrix, Precision, Recall, F1-Score.

### 4. Visualization (EDA)
Rich visualizations using **Seaborn** and **Plotly** (Interactive):
* 📊 **Histograms:** Distribution of tweet lengths.
* 🥧 **Interactive Pie Charts:** Sentiment distribution.
* 📈 **Stacked Bar Charts:** Sentiment breakdown by Airline.
* ☁️ **Word Clouds:** Most frequent words in negative vs. positive tweets.

## 🚀 How to Run

### Prerequisites
Make sure you have Python installed. You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn nltk wordcloud
