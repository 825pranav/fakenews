# Fake News Predictor

This project is a machine learning-based fake news detection system built using Python and Jupyter Notebook. It uses natural language processing (NLP) techniques to clean and vectorize news text data and then applies a classifier to predict whether a given news article is real or fake.

The model is trained using TF-IDF vectorization and a simple classifier like Logistic Regression or Passive Aggressive Classifier. It's suitable for educational projects, demos, and experimentation with text classification.

## Features

- Preprocessing of raw text (lowercasing, stopword removal, etc.)
- TF-IDF vectorization to convert text to numerical features
- Classification of articles into REAL or FAKE
- Evaluation using accuracy score and confusion matrix

## How to Run the Project

```bash
# 1. Clone this repository
git clone https://github.com/yourusername/fake-news-predictor.git
cd fake-news-predictor

# 2. Install required dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# 3. Launch the notebook
jupyter notebook fakenewspredictor.ipynb
