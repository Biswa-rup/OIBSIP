# Sales Prediction Using Python

## OASIS Infobyte – Data Science Internship

### Task 5: Sales Prediction Using Python

---

## 📌 Project Overview

This project focuses on predicting product sales based on advertising expenditure across three different media channels: **TV, Radio, and Newspaper**.

Exploratory Data Analysis (EDA), data visualization, regression models, and performance evaluation techniques are used to understand the relationship between advertising expenditure and sales.

Two machine learning models are developed and compared:

- Linear Regression
- Random Forest Regressor

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze the Advertising dataset.
- Clean and preprocess the data.
- Explore relationships between advertising channels and sales.
- Visualize the relationship between TV, Radio, Newspaper, and Sales.
- Build a Linear Regression model.
- Build a Random Forest Regression model.
- Evaluate the models using MAE, RMSE, and R².
- Compare the performance of both models.
- Identify the most influential advertising channel.
- Analyze model residuals.

---

## 📊 Dataset

The project uses the **Advertising Dataset**, which contains 200 observations.

### Features

| Feature | Description |
|---|---|
| TV | Advertising expenditure through TV |
| Radio | Advertising expenditure through Radio |
| Newspaper | Advertising expenditure through Newspaper |
| Sales | Product sales |

The target variable is:

**Sales**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Data Analysis

The following analyses were performed:

### 1. Data Inspection

- Dataset shape
- Column information
- Missing-value check
- Duplicate-value check
- Descriptive statistics

### 2. Exploratory Data Analysis

The following visualizations were created:

- Advertising channels vs Sales pairplot
- TV vs Sales scatter plot
- Radio vs Sales scatter plot
- Newspaper vs Sales scatter plot
- Correlation heatmap

### 3. Machine Learning

The dataset was divided into:

- 80% training data
- 20% testing data

Two regression models were trained:

#### Linear Regression

Linear Regression was used as the baseline model for predicting Sales.

#### Random Forest Regressor

Random Forest Regression was used as an additional machine learning model to compare its performance with Linear Regression.

---

## 📏 Evaluation Metrics

The models were evaluated using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

Lower MAE indicates better performance.

### Root Mean Squared Error (RMSE)

Measures prediction error while giving greater weight to larger errors.

Lower RMSE indicates better performance.

### R² Score

Measures how much of the variation in Sales is explained by the model.

Higher R² indicates better performance.

---

## 📈 Model Comparison

The performance of Linear Regression and Random Forest Regressor is compared using:

- MAE
- RMSE
- R² Score

The model with lower MAE and RMSE and higher R² is considered the better-performing model on the test dataset.

---

## ⭐ Feature Importance

Feature importance analysis was performed using the Random Forest model to determine which advertising channel contributes most strongly to the model's predictions.

The analysis includes:

- TV
- Radio
- Newspaper

The results are visualized using a feature-importance graph.

---

## 📉 Residual Analysis

A residual plot was created for the selected best-performing model.

Residual analysis helps determine whether prediction errors are randomly distributed around zero and whether there are any noticeable patterns in the errors.

---

## 📂 Project Structure

```text
DataScience-Task5-SalesPrediction/
│
├── Sales Prediction Using Python.ipynb
├── README.md
│
└── screenshots/
    ├── dataset_overview.png
    ├── descriptive_statistics.png
    ├── sales_vs_tv.png
    ├── sales_vs_radio.png
    ├── sales_vs_newspaper.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted_random_forest.png
    ├── model_comparison.png
    ├── feature_importance.png
    └── residual_plot.png
