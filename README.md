# 📊 Dotchin.com Customer Retention & Marketing Campaign Analysis

This project analyzes historical marketing and customer interaction data from **Dotchin.com**, a direct-to-consumer online retail platform. The objective is to build predictive models that enhance customer engagement and retention through data-driven insights.

---

## 📌 Project Summary

- **Project**: Internal Analytics – Customer Retention Optimization  
- **Author**: Seyed Mohammad Mehdi Hassani Najafabadi  
- **Platform**: Dotchin.com (2018–2021)  
- **Dataset**: Aggregated user interaction and purchase funnel data from Dotchin.com's CRM and marketing campaigns

---

## 🧠 Objectives

- Predict the likelihood of a customer completing a purchase (conversion).
- Understand the drivers of customer drop-off in the marketing funnel.
- Compare the performance of four machine learning classifiers:
  - Decision Tree (DT)
  - Random Forest (RF)
  - Gradient Boosting Classifier (GBC)
  - Support Vector Machine (SVM)

---

## 🧪 Methods

To model and evaluate customer conversion, we applied:
- **Data preprocessing** of numeric and categorical features.
- **K-Fold Cross Validation** for robust evaluation.
- Classifier performance measured using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC

---

## 📈 Key Findings

- **Top Predictors**: Session duration, last interaction date, number of touchpoints, user balance (purchase value).
- **Best Classifier**: Random Forest showed the most consistent and accurate results.
- **Insights**:
  - Customers with longer sessions and multiple contact points were more likely to convert.
  - Retargeting campaigns during peak shopping periods (e.g., pre-holidays) improved engagement.
  - Over-contacting users led to diminishing returns in conversion effectiveness.

---

## 📊 Visualizations

The analysis includes:
- Funnel conversion drop-off charts
- Distribution plots for categorical and numerical features
- ROC curves for classifier comparisons
- Feature importance visualizations

---

## 📁 Project Structure

```text
├── data/                       # Dotchin CRM & marketing funnel exports
├── notebooks/                 # EDA and model training notebooks
├── models/                    # Trained model outputs
├── visuals/                   # Marketing funnel and feature plots
├── README.md
└── requirements.txt           # Python dependencies
