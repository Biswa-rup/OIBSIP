# 📧 Email Spam Detection using Machine Learning

A machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and TF-IDF feature extraction.

> **OASIS Infobyte Data Science Internship — Task 4**

---

## 📌 Project Overview

Spam messages are unwanted messages that may contain advertisements, fraudulent offers, or misleading content. This project develops a machine learning-based spam detection system capable of automatically classifying SMS messages.

The project uses the **SMS Spam Collection Dataset** and compares three machine learning algorithms:

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (SVM)

The models are evaluated using Accuracy, Precision, Recall, and F1-Score.

---

## 🎯 Objectives

- Load and explore the SMS spam dataset.
- Clean and preprocess the text data.
- Analyze the distribution of Spam and Ham messages.
- Convert text into numerical features using TF-IDF.
- Split the dataset into training and testing sets.
- Train multiple machine learning models.
- Compare model performance.
- Generate confusion matrices and visualizations.
- Build a system for predicting new SMS messages.

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**.

### Dataset Statistics

| Category | Count |
|----------|------:|
| Total Messages | 5,572 |
| Ham Messages | 4,825 |
| Spam Messages | 747 |

The original dataset contains:

- `v1` — Message label (`ham` / `spam`)
- `v2` — SMS message text

During preprocessing, these columns are renamed to:

- `label`
- `message`

The additional columns present in the CSV are removed because they are not required for classification.

---

## 🔄 Project Workflow

```text
SMS Spam Dataset
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Text Preprocessing
       ↓
TF-IDF Feature Extraction
       ↓
Train-Test Split
       ↓
Machine Learning Models
       ↓
Model Evaluation
       ↓
Model Comparison
       ↓
Spam/Ham Prediction
