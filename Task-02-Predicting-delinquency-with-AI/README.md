# 🧠 Task 2: Predicting Delinquency with AI  
**Geldium | Tata Data Analytics Virtual Internship**  
**Source**: [Tata Forage Simulation](https://www.theforage.com/simulations/tata/data-analytics-t3zr?reloaded=true)

---

## 📌 Overview

This task focuses on using AI to predict which credit card customers are at the highest risk of delinquency. Building on the exploratory data analysis (Task 1), this phase outlines a structured predictive modeling approach that supports Geldium’s collections strategy by identifying high-risk customers early and accurately.

---

## 🎯 Objectives

- Design a predictive model to classify customers at risk of missing payments.
- Select and justify the most suitable machine learning model.
- Define an evaluation framework that ensures accuracy, fairness, and explainability.

---

## 🔍 Step 1: Model Logic

### ✅ Model Chosen: Logistic Regression  
- **Reason**: Interpretable, easy to deploy, well-suited for binary classification tasks like delinquency prediction.
- **Backup Option**: Random Forest – useful for more complex, non-linear relationships but less explainable.

### ⭐ Top 5 Input Features
1. Credit Utilization Rate  
2. Number of Missed Payments  
3. Debt-to-Income Ratio  
4. Income Level  
5. Customer Tenure

### 🔁 How the Model Works
- Preprocess inputs: handle missing values, scale numerical features, and encode categoricals.
- Feed features into a logistic regression model trained on labeled historical data.
- Generate a probability score between 0 and 1 indicating delinquency risk.
- Classify customers based on a threshold (e.g., 0.5) into "high risk" or "low risk".
- Use risk scores to prioritize outreach by the Collections team.

---

## 🧠 Step 2: Model Justification

Logistic regression was chosen for its simplicity, interpretability, and strong fit with the binary nature of delinquency prediction. In financial services, models must be explainable to meet regulatory requirements and build stakeholder trust. Unlike black-box models (e.g., neural networks), logistic regression clearly shows how each variable influences the prediction. It allows Geldium to make transparent, fair, and auditable decisions that align with its operational goals and ethical standards.

---

## 📏 Step 3: Evaluation Strategy

A well-rounded evaluation framework was developed to ensure both performance and fairness:

### 📊 Performance Metrics
- **Accuracy** – General prediction correctness
- **Precision** – Correctness of predicted delinquents
- **Recall** – Ability to detect actual delinquents
- **F1 Score** – Balance of precision and recall
- **AUC-ROC** – Overall model discrimination ability

### ⚖️ Fairness & Bias Checks
- **Demographic Parity** – Equal outcomes across groups
- **Disparate Impact** – Identify and mitigate unequal treatment
- **Explainability** – Use SHAP to understand feature contributions

If bias is detected, mitigation strategies like rebalancing, proxy feature removal, and threshold adjustment will be applied.

---

## 🛠 Tools Used

- GenAI tools (e.g., ChatGPT) for model design, evaluation planning, and ethical review
- Python (conceptually) for modeling logic and pipeline structuring
- Excel dataset from Task 1 (no code execution required)

---

## 🙏 Acknowledgments

This project was completed as part of the **Tata Data Analytics Virtual Experience Program** on [Forage](https://www.theforage.com/simulations/tata/data-analytics-t3zr?reloaded=true).  
All data and scenarios are simulations intended for educational purposes only.

---

