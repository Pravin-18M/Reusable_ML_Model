# Text Classification using Multinomial Naive Bayes

This project classifies text documents from the scikit-learn
20 Newsgroups dataset using TF-IDF Vectorization and
Multinomial Naive Bayes.

## Files

- train.py - Trains, evaluates and saves the ML model.
- requirements.txt - Contains required Python dependencies.
- 20newsgroups_model.joblib - Saved trained ML model.

## Machine Learning Pipeline

Text
↓
TF-IDF Vectorizer
↓
Multinomial Naive Bayes
↓
Predicted Category

## How to Run

Install dependencies:

pip install -r requirements.txt

Run the training script:

python train.py