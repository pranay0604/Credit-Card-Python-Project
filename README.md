# 💳 Credit Card Fraud Detection – Data Analysis Project

## 📘 Overview

This project analyzes credit card transaction data to identify fraudulent behavior. Using real-world, anonymized data, the focus is on understanding patterns that can support fraud detection models.

The dataset is highly imbalanced (only ~0.17% fraud), making this a practical case for anomaly analysis.

---

## 🎯 Objectives

**Primary Goal:**
- Explore transaction-level data to identify patterns in fraudulent behavior.

**Secondary Goals:**
- Compare fraud vs. non-fraud transactions by amount and time.
- Analyze the effectiveness of certain anonymized features in detecting fraud.
- Visualize the class imbalance and its implications.

---

## 🗃️ Dataset

- **Name:** Credit Card Fraud Detection  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Rows:** 284,807  
- **Columns:** 31 (Time, Amount, 28 anonymized features, Class)

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 📊 Key Findings

- **Fraudulent transactions** are usually smaller in amount.
- Features like **V14, V12, and V10** show strong separation between classes.
- The dataset’s class imbalance highlights the importance of advanced techniques like SMOTE or anomaly detection for model training.

---

## 📈 Visuals

- Distribution plots for transaction amounts
- Boxplots for fraud vs. non-fraud analysis
- Correlation heatmaps

---

## 🧠 Takeaway

Banks can improve fraud detection systems by monitoring key indicators and adjusting thresholds around sensitive features. This kind of exploratory analysis can guide the development of real-time fraud scoring models.

---

## 📎 References

- Kaggle Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## 🙋 Author

**Name:** *Pranay Sontakke*  
**GitHub:** [github.com/pranay0604](https://github.com/pranay0604)  
**LinkedIn:** [www.linkedin.com/in/pranay-sontakke](www.linkedin.com/in/pranay-sontakke)
