📧 Email Spam Detection using SVM, Logistic Regression & Random Forest
🔹 Introduction

This project is about detecting whether an email is spam or ham (not spam).
I built a machine learning model that learns patterns from emails and classifies them correctly.

🔹 Motivation

Email spam wastes time and may contain harmful links.

I wanted to apply machine learning (ML) and natural language processing (NLP) to solve this real-world problem.

By comparing different ML models, I can see which one works best for spam detection.

🔹 Tools & Technology

Python

Google Colab / Jupyter Notebook

scikit-learn (ML models)

NLTK (text preprocessing: stopwords, stemming)

pandas, numpy (data handling)

🔹 Machine Learning Models Used

Logistic Regression – simple and effective for text classification.

Support Vector Machine (SVM) – powerful for separating spam vs ham.

Random Forest – ensemble method for better accuracy and stability.

🔹 How It Works

Load dataset (emails labeled as spam or ham).

Clean the text (remove stopwords, punctuation, stemming).

Convert text to numbers using TF-IDF vectorizer.

Train models (LR, SVM, RF).

Predict whether new email is spam or ham.

🔹 Future Scope

Deploy as a web app to detect spam in real time.

Add deep learning models (RNN, LSTM, BERT) for better accuracy.

Handle multilingual spam detection.

Optimize for faster predictions in production.
