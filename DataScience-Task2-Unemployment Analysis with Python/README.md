# Unemployment Analysis with Python

## OASIS Infobyte – Data Science Internship

### Task 2: Unemployment Analysis with Python

This project performs Exploratory Data Analysis (EDA) on unemployment data from India to understand regional and temporal unemployment trends, including the impact of the COVID-19 pandemic.

---

## 📌 Objective

The main objective of this project is to analyze unemployment rates across different regions of India and identify important patterns and trends in employment and labour participation.

The analysis focuses on:

- Regional unemployment rates
- Monthly unemployment trends
- Employment statistics
- Labour participation rates
- Comparison between regions
- Pre-COVID and post-COVID unemployment trends
- Relationship between unemployment, employment and labour participation

---

## 📊 Dataset

The dataset used in this project is **Unemployment in India**.

The dataset contains information about:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

Dataset size after cleaning:

- **768 rows**
- **7 columns**
- **28 regions**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Data Analysis Performed

### 1. Data Loading and Cleaning

The dataset was loaded using Pandas and cleaned by:

- Removing unnecessary spaces from column names
- Converting the Date column into datetime format
- Converting numerical columns into appropriate data types
- Handling missing values
- Removing duplicate records

### 2. Exploratory Data Analysis

Statistical analysis was performed to understand:

- Mean unemployment rate
- Minimum and maximum unemployment rate
- Employment statistics
- Labour participation rate
- Regional distribution

### 3. Visualizations

The following visualizations were created:

- Dataset overview
- Distribution of unemployment rates
- Regional unemployment comparison
- Monthly unemployment trend
- Top 10 regions with highest unemployment
- Correlation heatmap
- Pre-COVID vs Post-COVID comparison
- Percentage distribution of unemployment

---

## 📈 Key Observations

### Regional Analysis

Unemployment rates vary significantly across different regions of India. Some regions consistently show higher unemployment rates than others.

### Monthly Trend

The unemployment rate changes over time, showing noticeable fluctuations during different periods.

### COVID-19 Impact

The analysis shows a significant change in unemployment levels during the COVID-19 period, highlighting the effect of the pandemic on employment.

### Labour Participation

Labour participation rates also vary across regions and show a relationship with employment and unemployment conditions.

### Dataset Distribution

The dataset contains observations from multiple regions and periods, allowing regional and time-based comparisons.

---

## 📂 Project Structure

```text
DataScience-Task2-UnemploymentAnalysis/
│
├── Unemployment Analysis with Python.ipynb
├── README.md
│
└── screenshots/
    ├── dataset_overview.png
    ├── regional_comparison.png
    ├── monthly_trend.png
    ├── top_10_regions.png
    ├── correlation_heatmap.png
    └── pre_post_covid_comparison.png
