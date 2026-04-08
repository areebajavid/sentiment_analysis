# 🎬 Movie Review Sentiment Analysis

### *Predict if a movie review is Positive or Negative using Logistic Regression*

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat&logo=scikit-learn)](https://scikit-learn.org)

---

## What It Does

Enter a movie review → Model predicts sentiment as **Positive** or **Negative**.

**Dataset:** 1000 balanced movie reviews (500 positive, 500 negative)

**Model:** Logistic Regression with TF-IDF vectorization

**Accuracy Metrics:**
| Metric | Value |
|--------|-------|
| Training Data | 800 reviews |
| Testing Data | 200 reviews |
| Confusion Matrix | Viewable in notebook |

---

## How It Works



**Tech Stack:** Python, Scikit-Learn, Streamlit, Pandas, NLTK, WordCloud

**Data Processing:**
- Removed stopwords (the, a, an, etc.)
- TF-IDF vectorization with 2500 max features
- Balanced dataset (500 positive, 500 negative)

---

## Quick Start

```bash
# Install dependencies
pip install streamlit pandas scikit-learn nltk wordcloud matplotlib

# Run the app
streamlit run app.py

Or use the Jupyter notebook (Movie_review_Model_Creation.ipynb) to retrain the model.

Sample Output
Input	Prediction
"This movie was amazing!"	Positive Review
"Waste of time, terrible acting"	Negative Review


Files: model.pkl (trained model) | scaler.pkl (TF-IDF vectorizer) | Movie_Review.csv (dataset)


---

## About Section for GitHub

**Short description:**
