# Spam Detection Project 🚀

[![Python](https://img.shields.io/badge/Python-3.12-blue)](https://www.python.org/) 
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Project Overview
This project is a **Spam Detection system** that classifies messages (emails or text) as **spam** or **non-spam**. It leverages **Machine Learning** and **Natural Language Processing (NLP)** techniques to provide accurate and fast predictions.

---

## Key Features
- **Text Preprocessing**: cleaning, tokenization, stopword removal
- **Feature Extraction**: TF-IDF or CountVectorizer
- **Machine Learning Models**:
  - Naive Bayes
  - Logistic Regression
  - Random Forest
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score
- **Web Interface**: FastAPI/Flask for real-time prediction

---

## Project Structure

Spam_Detection/
│ 
├── Data/                                          # Dataset and notebooks
│ └── spam.csv
├── src/                                         # Source code
│ ├── components/                                 # Modular functions
│ ├── Pipeline/                                 # ML pipeline scripts
│ ├── logger.py                                   # Logging utility
│ └── exception.py                               # Custom exceptions
├── app.py                                       # Main web application
├── requirements.txt                           # Python dependencies
├── setup.py                                     # Package setup
└── README.md                                     # Project documentation


