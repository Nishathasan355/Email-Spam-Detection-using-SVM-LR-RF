# Email Spam Detection
*Using SVM, Logistic Regression, and Random Forest*

---

## Introduction
This project detects whether an email is **Spam** or **Ham (Not Spam)** using machine learning.
It applies **Natural Language Processing (NLP)** techniques to clean email text and trains classifiers to identify spam patterns.

---

## Motivation
- Spam emails waste time and may contain harmful links.
- Machine learning provides an effective solution for **automatic spam filtering**.
- Testing multiple models (SVM, LR, RF) helps find the best performer.

---

## Tools & Technology
- **Python**
- **Jupyter / Google Colab**
- **scikit-learn** → Machine Learning models
- **NLTK** → Text preprocessing
- **pandas & numpy** → Data handling

---

## Models Used
- **Logistic Regression** → Simple, interpretable baseline
- **Support Vector Machine (SVM)** → Strong at separating spam vs ham
- **Random Forest** → Ensemble model for better stability

---

## Workflow
1. Load dataset (emails labeled spam/ham)
2. Clean text (remove stopwords, punctuation, stemming)
3. Convert text into vectors (CountVectorizer / TF-IDF)
4. Train ML models (LR, SVM, RF)
5. Predict new emails → Spam or Ham

---

## Future Scope
- Deploy as a **web app** for real-time spam detection
- Add **deep learning models (RNN, LSTM, BERT)**
- Support **multilingual spam detection**
- Optimize for faster predictions

---

## How to Run
```bash
# Clone repository
git clone https://github.com/your-username/Email-Spam-Detection-using-SVM-LR-RF.git

# Open Jupyter Notebook
jupyter notebook emailspam.ipynb
