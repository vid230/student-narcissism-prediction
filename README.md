

# 🧠 Data-Driven Insights into Anxiety Disorders

## 📋 Project Overview

This project aims to explore and understand the patterns behind anxiety disorders using Exploratory Data Analysis (EDA) and data preprocessing techniques. The dataset used is sourced from Kaggle and focuses on the impact of gaming behavior on anxiety levels, narcissism, and related psychological factors.

## 👩‍💻 Authors
* Prashant Uppar - [02fe22bcs069@kletech.ac.in](mailto:02fe22bcs069@kletech.ac.in)
* Chandni Kumari - [02fe22bcs026@kletech.ac.in](mailto:02fe22bcs026@kletech.ac.in)
* Wilfred Antonio Borges - [02fe22bcs177@kletech.ac.in](mailto:02fe22bcs177@kletech.ac.in)
* Yukta Sannaki - [02fe22bcs179@kletech.ac.in](mailto:02fe22bcs179@kletech.ac.in)

## 📁 Dataset

* Source: [Kaggle](https://www.kaggle.com/)
* Records: 13,464
* Features: 55 columns including psychological scores, gaming habits, demographics, and behavioral traits.

## 🔍 Objectives

* Perform data cleaning and preprocessing.
* Handle missing values and outliers.
* Perform univariate, bivariate, and multivariate analysis.
* Understand correlations between features.
* Generate insights into how gaming behaviors are linked to anxiety and narcissism.

## ⚙️ Key Steps

### 1. Data Preprocessing

* **Null Handling:** Used imputation methods based on data type and distribution (mean, median, mode).
* **Outlier Handling:** Removed only significant outliers that influenced trends.
* **Encoding:** Applied label encoding and binning for categorical variables.
* **Feature Selection:** Dropped unnecessary columns (e.g., timestamp, redundant assessment items).

### 2. Visualization

* Plotted KDEs, boxplots, pie charts, histograms, and heatmaps.
* Analyzed relationships such as:

  * Platform vs Narcissism
  * Game vs Anxiety
  * Hours spent vs Social Phobia
  * Satisfaction with Life vs General Anxiety

### 3. Key Findings

* Majority of the affected individuals are students aged \~20, often gaming on PCs.
* Strong correlation between gaming hours and narcissism levels.
* Social phobia is inversely correlated with satisfaction in life.

## 🛠 Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook / Google Colab
* Scikit-learn (for data transformation and modeling)

## 📈 Future Work

* Apply machine learning models to validate and predict anxiety levels using features refined in this EDA.

---

## ✅ Model Implemented

Although the primary focus of the project was on EDA, **Logistic Regression** was implemented to evaluate its suitability in predicting psychological traits like narcissism based on behavioral data.

