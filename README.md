# 📘 Twitter Sentiment Analysis using PySpark and Logistic Regression

## 📝 Project Description

This project focuses on performing sentiment analysis on a large-scale Twitter dataset. The goal is to classify tweets as **positive** or **negative** using **PySpark MLlib** and **Logistic Regression** for scalable machine learning. The pipeline includes data cleaning, preprocessing, feature extraction, and model evaluation using real-world tweets.

---

## 🧩 Key Features

- Preprocessing and cleaning of noisy tweet text:
  - Removal of Twitter mentions (@username)
  - Elimination of URLs, HTML tags, emojis, hashtags, and special characters
  - Text normalization: lowercasing, tokenization, stopword removal, and lemmatization
- Text vectorization using:
  - `Tokenizer`
  - `CountVectorizer` or `HashingTF + IDF`
  - `N-Grams` (bigrams/trigrams) for feature enhancement
- Sentiment classification using **Logistic Regression** from Spark MLlib
- Model evaluation with:
  - ✅ **Accuracy**
  - 📐 **F1 Score**
  - 📊 **Confusion Matrix**
  - 🧮 **ROC-AUC Curve**
- Deployed a prediction function for **real-time sentiment detection**
- Created **WordCloud** visualizations for:
  - Most frequent words in **positive tweets**
  - Most frequent words in **negative tweets**

---

## 🔧 Tools & Technologies

- 🐍 Python
- ⚡ PySpark (Spark MLlib)
- 📊 Pandas, Matplotlib
- 🧹 BeautifulSoup, Regex, NLTK
- 📒 Jupyter / Google Colab Notebooks


---

## 🧾 Dataset Description

**Columns in the dataset:**

- `sentiment`: Target variable (0 = negative, 4 = positive)
- `id`: Unique identifier for each tweet
- `date`: Date and time of the tweet
- `query_string`: The query used to collect the tweet (not useful for sentiment analysis)
- `user`: Username of the person who tweeted
- `text`: Actual tweet content

---

## 📊 Sample Output

- **Accuracy**: ~82%
- **ROC-AUC Score**: ~0.85
- **Real-time sentiment prediction**: ✅ Supported

---
