# NLP – Sentiment Analysis on Restaurant Reviews

This project applies supervised machine learning to classify restaurant reviews as positive (Liked = 1) or negative (Liked = 0). The dataset contains 1,000 reviews labeled with sentiment.

## Dataset

File: Dataset2.tsv

Columns:

Review → the customer’s feedback text

Liked → target label (1 = Positive, 0 = Negative)

Example:

Review	Liked
Wow... Loved this place.	1
Crust is not good.	0
The fries were great too.	1

## Steps in the Pipeline

### Data Loading & Exploration

Used pandas to load and inspect dataset

Shape: (1000, 2) → 1000 reviews

### Text Preprocessing

Removal of punctuation and special characters with regex (re)

### Tokenization of text

Removal of stopwords (using NLTK stopwords corpus)

Optional: stemming/lemmatization

### Feature Extraction

Transforming reviews into numerical vectors (e.g., Bag of Words, TF-IDF)

### Model Training

Supervised learning with classifiers (Naive Bayes, Logistic Regression, SVM, etc.)

### Evaluation

Accuracy, precision, recall, F1-score

## Objective

To build a system that can automatically predict whether a restaurant review is positive or negative, serving as a baseline for sentiment analysis in NLP applications.
