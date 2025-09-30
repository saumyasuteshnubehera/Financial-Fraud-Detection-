# Financial Fraud Detection

 ## 📌 Project Overview
 <img width="334" height="500" alt="Financial Fraud Detection Infographic (1)" src="https://github.com/user-attachments/assets/003068a9-1c74-4191-abfb-a38c90b0beac" />

### This project addresses the challenge of detecting fraudulent credit card transactions, a classic case of highly imbalanced data where frauds make up less than 0.2% of total transactions.

## The solution combines:

### • Exploratory Data Analysis (EDA) to understand fraud behavior

### • Anomaly Detection Models (Isolation Forest + DBSCAN with PCA)

### • SQL-based querying for analytical insights

### • Power BI Dashboard for interactive fraud monitoring

## 🎯 Objectives

### • Explore fraud vs. normal transaction patterns.

### • Build unsupervised anomaly detection models suitable for imbalanced datasets.

### • Tune thresholds to improve recall for fraud cases.

### • Provide business-friendly insights through Power BI dashboards.

## 🛠️ Tech Stack

### • Programming: Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn)

### • Anomaly Detection: Isolation Forest, DBSCAN, PCA

### • Database: SQLite + SQL queries

### • Visualization: Power BI

### • Other Tools: Jupyter Notebook

## 📊 Dashboard Highlights

<img width="587" height="334" alt="image" src="https://github.com/user-attachments/assets/af410c71-93f4-4100-8a14-54d1b0dafd70" />

### • The Power BI dashboard visualizes:

### • Total Transactions: 284,807

### • Fraud Cases: 492 (≈0.17%)

### • Fraud Amount vs. Normal Amount

### • Fraud distribution by time of day

### • Filters for transaction type, amount, and PCA features

## 🚀 Workflow

### 1. Data Preprocessing & EDA

#### • Removed duplicates (1081).

#### • Checked missing values → none found.

#### • Scaled transaction amounts with StandardScaler.

#### • Extracted Hour feature from transaction time.

#### • Visualized transaction amounts, fraud distribution, and feature correlations.

### 2. Anomaly Detection Models

#### • Isolation Forest: Trained on scaled features with contamination detection.

#### • DBSCAN + PCA: Reduced dimensionality for clustering anomalies.

#### • Combined approach: Merged results from Isolation Forest & DBSCAN.

#### • Threshold tuning: Improved recall for fraud transactions.

### 📌 Best Results (Isolation Forest tuned):

#### • Accuracy: 99.78%

#### • Fraud Recall: ~34% (detected 1 in 3 fraud cases)

#### • Fraud Precision: ~35%

### 3. SQL Analysis

#### • Counted total vs. fraud transactions.

#### • Calculated fraud percentage (0.17%).

#### • Fraud transactions by hour of day → peak at 11 AM–12 PM.

#### • Analyzed PCA features (e.g., V14 strongly correlated with fraud).

### 4. Visualization in Power BI

#### • Designed interactive dashboard for fraud monitoring.

#### • KPI cards (fraud %, fraud amount, max fraud transaction).

#### • Distribution plots and filters for deeper insights.

## 📈 Key Insights

#### • Fraud transactions are very rare (≈0.17%).

#### • Fraudulent amounts are smaller than typical transaction amounts.

#### • Fraud shows time-of-day patterns (peaks around 11 AM).

#### • PCA feature V14 < -5 is a strong fraud indicator.

## 👥 Project Collaboration

## This project was completed as part of an internship group project.

### My Contributions

#### • Data Collection (From Kaggle)

#### • Data cleaning and preprocessing (duplicates removal, missing value check, normalization).

#### • Exploratory Data Analysis (EDA): fraud vs. non-fraud distributions, transaction amount patterns, feature correlations.

#### • Feature engineering: Extracted Hour of transaction and analyzed fraud distribution by time of day.

#### • Visualizations using Matplotlib & Seaborn to uncover key insights.

### Contributions by Teammates

#### • Model building (Isolation Forest, DBSCAN, PCA).

#### • Model evaluation and hyperparameter tuning.

#### • SQL queries for fraud transaction insights.

#### • Dashboard design in Power BI

#### • Final documentation.

## 💼 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/saumyasuteshnu-behera-50a478209/)
