
SMS Spam Detection
An NLP-based machine learning project that classifies SMS messages as spam or ham (not spam) using Naive Bayes and Decision Tree classifiers with TF-IDF vectorization.

📌 Problem Statement
Spam messages are a major nuisance and security threat. This project builds a text classification pipeline to automatically detect and filter spam SMS messages using natural language processing techniques.

📂 Dataset

Source: SMS Spam Collection Dataset
Size: ~5,500 SMS messages
Classes: Ham (legitimate) and Spam
Challenge: Class imbalance handled via oversampling


🛠️ Technologies Used

Python
Pandas, NumPy
Scikit-learn (Naive Bayes, Decision Tree, TF-IDF)
NLTK (Lemmatization, Stopword Removal)
Matplotlib, Seaborn


⚙️ Methodology

Exploratory Data Analysis (EDA) — Message length distribution, spam vs ham ratio
Feature Engineering

Word count per message
Currency symbol detection
Special character count


Text Preprocessing

Lowercasing, punctuation removal
Stopword removal
Lemmatization using NLTK


Vectorization — TF-IDF (Term Frequency-Inverse Document Frequency)
Class Imbalance — Handled via oversampling
Models:

Multinomial Naive Bayes
Decision Tree Classifier


Evaluation — 10-fold Cross Validation, Precision, Recall, F1-Score


📊 Results
ModelAccuracyMultinomial Naive Bayes~94% Decision Tree~99%
