# Task 1: Exploratory Data Analysis and Risk Profiling

## 📌 Project Context

This repository contains the work completed for **Task 1** of the AI-powered credit risk analytics project with **Geldium**, a digital lending and consumer credit company. This task is part of the **Tata Data Analytics Virtual Experience Program** offered on [Forage](https://www.theforage.com/simulations/tata/data-analytics-t3zr?reloaded=true).

The project focuses on reducing credit card delinquency by using AI-driven insights to identify at-risk customers and guide the Collections team toward timely, targeted interventions.

---

## 🎯 Objective

The primary goal of this task was to conduct **Exploratory Data Analysis (EDA)** to:

- Assess the quality and structure of the provided financial dataset
- Identify missing values and recommend appropriate imputation strategies
- Uncover patterns and early indicators of delinquency risk
- Document high-risk variables and actionable insights for predictive modeling

---

## 🧪 Steps Performed

### 1. **Data Quality Analysis**
- Reviewed 500 customer records with 19 attributes
- Identified key missing features: `Income` (7.8%), `Loan_Balance` (5.8%), `Credit_Score` (0.4%)
- Detected possible outliers in `Credit_Utilization` (values >1.0)

### 2. **Missing Value Handling**
- Suggested statistical imputation for low-missing variables
- Generated synthetic `Income` data using normal distribution assumptions to maintain realism and privacy
- Recommended regression-based imputation for financial variables with logical correlations

### 3. **Risk Pattern Detection**
- Analyzed relationships between variables (e.g., `Missed_Payments`, `Credit_Utilization`, `Debt_to_Income_Ratio`) and delinquency
- Found strong positive correlation between `Missed_Payments` and `Delinquent_Account`
- Detected that high credit utilization aligns with increased delinquency risk

### 4. **Risk Indicators Identified**
- **Missed_Payments**: High frequency indicates higher future risk
- **Credit_Utilization**: Usage beyond 90% of the limit suggests financial strain
- **Debt_to_Income_Ratio**: Higher values correlate with increased default likelihood

---

## 🧠 Tools and Techniques Used

- Python (Pandas, NumPy) for EDA
- GenAI-assisted prompts for summarization and synthetic data generation
- Statistical techniques (mean, median imputation, normal distribution modeling)
- Domain-aligned practices to preserve fairness and transparency

---

## 📄 Deliverables

- `EDA_SummaryReport.docx`: EDA findings, missing value treatment plan, and early risk indicators
- Cleaned dataset with proposed imputations (not included due to confidentiality)
- Insights for shaping the next stage: predictive modeling and intervention planning

---

## 🏷️ Source and Credits

This task is based on the simulation experience provided by:

**Tata Data Analytics Virtual Experience Program**  
🔗 [The Forage – Tata iQ Simulation](https://www.theforage.com/simulations/tata/data-analytics-t3zr?reloaded=true)  
Developed by Tata iQ to simulate real-world analytics consulting projects.

---
--
