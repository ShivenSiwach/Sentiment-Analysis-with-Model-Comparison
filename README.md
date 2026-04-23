# Sentiment Analysis with Model Comparison

This project is a Natural Language Processing (NLP) and machine learning notebook built in **Google Colab** for sentiment classification on movie reviews. It uses the **IMDb movie review dataset** to classify reviews as **positive** or **negative** and compares the performance of multiple machine learning models.

The project demonstrates a complete NLP workflow including text preprocessing, TF-IDF vectorization, model training, model comparison, and evaluation using standard classification metrics.

This is a strong foundational portfolio project for:

- Data Analyst
- Machine Learning Intern
- NLP Intern
- AI Associate
- Python Developer
- Data Science Intern

---

## Project Type

This project was developed and executed in **Google Colab** as a **notebook-based machine learning workflow**.

It is designed to demonstrate:

- NLP preprocessing
- Text feature engineering
- Classical machine learning for text classification
- Model benchmarking
- Evaluation and interpretation of results

> Note: This repository is currently a **Colab / notebook-first project**, not a deployed web application.

---

## Project Overview

The goal of this project is to build a binary sentiment classifier that automatically determines whether a movie review expresses:

- **Positive sentiment**
- **Negative sentiment**

Instead of using only one model, this project compares multiple machine learning algorithms on the same dataset to identify the best-performing approach.

This project covers:

- Data loading
- Text preprocessing
- TF-IDF vectorization
- Model training
- Model comparison
- Performance evaluation
- Prediction on unseen reviews

---

## Problem Statement

Large volumes of text data such as reviews, feedback, and comments are difficult to analyze manually.

This project solves that problem by:

- Cleaning and preprocessing text data
- Transforming text into numerical features using **TF-IDF**
- Training classification models
- Comparing their performance
- Predicting sentiment automatically

---

## Dataset

This project uses the **IMDb Movie Reviews Dataset** containing **50,000 movie reviews** labeled as positive or negative.

### Dataset Characteristics
- Binary sentiment classification
- Balanced dataset
- Real-world user-generated text
- Common benchmark dataset for NLP tasks

### Target Labels
- `positive`
- `negative`

---

## Key Features

### Text Preprocessing
- Lowercasing
- Tokenization
- Stopword removal
- Punctuation removal
- Text cleaning for improved model performance

### Feature Engineering
- TF-IDF vectorization
- Conversion of raw text into numerical features
- Sparse matrix representation for ML models

### Model Training
The notebook compares multiple machine learning models such as:

- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

### Model Evaluation
Performance is evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

### Prediction
- Predicts sentiment for unseen reviews
- Demonstrates complete inference workflow

---

## Model Performance Summary

Based on the project results:

- **Logistic Regression:** **88.77% Accuracy**
- **Naive Bayes:** **85.1% Accuracy**
- **Support Vector Machine (SVM):** **87.3% Accuracy**

### Best Performing Model
**Logistic Regression** achieved the best performance and served as the strongest baseline model in this project. :contentReference[oaicite:0]{index=0}

---

## Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **NLTK**
- **Scikit-learn**
- **Matplotlib** (if used)
- **Seaborn** (if used)

---

## Notebook Workflow

This project follows a standard NLP pipeline inside Google Colab.

### 1. Import Libraries
Load all required Python libraries for data handling, NLP, and machine learning.

### 2. Load Dataset
Read the IMDb review dataset into a DataFrame.

### 3. Preprocess Text
Apply preprocessing steps such as:
- lowercasing
- tokenization
- stopword removal
- punctuation removal

### 4. Convert Text to Features
Use **TF-IDF Vectorizer** to transform review text into machine learning-ready numerical vectors.

### 5. Train/Test Split
Split the dataset into training and testing sets.

### 6. Train Multiple Models
Train and compare:
- Logistic Regression
- Naive Bayes
- SVM

### 7. Evaluate Models
Compare model performance using:
- Accuracy
- Confusion matrix
- Precision / Recall / F1-score
- Classification report

### 8. Predict on New Reviews
Use the best-performing model to classify new unseen reviews.

---

## Repository Structure (Notebook-Based)

```bash
Sentement_analysis/
│── Sentiment_Analysis.ipynb
│── README.md
│── requirements.txt        # Optional but recommended
│── sample_output.png       # Optional
