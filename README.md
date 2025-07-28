# 📊 Customer Sentiment & Churn Risk Analysis

This project combines **structured customer data** and **unstructured text feedback** to predict customer churn and derive actionable business insights using **machine learning**, **sentiment analysis**, and **customer segmentation**.

---

## 📌 Project Goals

- Predict customer churn using machine learning models.
- Analyze customer sentiment from feedback text.
- Segment customers based on churn probability and sentiment.
- Deliver actionable recommendations to reduce churn and improve customer satisfaction.

---

## 🧾 Dataset Overview

- **Structured Data**: Demographics, tenure, contract type, monthly charges, churn label.
- **Unstructured Data**: Customer feedback (support tickets, reviews).
- **Target**: `Churn` (binary classification: Yes / No).

---

## 🔍 Key Steps

### 1. 🧹 Data Preprocessing
- Handled missing values and inconsistent formats.
- Encoded categorical variables and normalized numerical ones.

### 2. 💬 Sentiment Analysis
- Applied `VADER` to score sentiment of customer feedback.
- Created a new feature: `SentimentScore`.

### 3. 🤖 Churn Prediction
- Models: Logistic Regression, Random Forest, XGBoost.
- Evaluation Metrics: Accuracy, AUC-ROC, Precision, Recall.
- Feature Importance analysis using SHAP (optional).

### 4. 📈 Customer Segmentation
- Used KMeans to cluster customers by churn probability and sentiment score.
- Segments include: Loyal Promoters, At-Risk Detractors, Passive Neutrals.

### 5. 📊 Visualization & Insights
- Churn by contract type, payment method, tenure, and sentiment.
- Cluster visualization with PCA.

---

## ✅ Results

- Achieved AUC score of **X.XX** and Accuracy of **XX%** (fill from your model).
- Identified that customers with low sentiment and month-to-month contracts are **highly likely to churn**.
- Created 3 actionable customer segments for targeting.

---

## 💡 Business Recommendations

- 🟡 **Target low-sentiment, high-risk customers** with retention offers.
- 🔵 **Upsell long-term contracts** to passive users with positive sentiment.
- 🟣 **Monitor feedback channels** using real-time sentiment analysis.

---

## 📂 File Structure

