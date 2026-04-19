# BCG X Data Science Virtual Experience - Customer Churn Analysis

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📌 Project Overview
This repository contains my work for the **BCG Data Science Job Simulation** on Forage. The project involves a strategic analysis of customer churn for **PowerCo**, a major energy utility, to help them understand why customers are leaving and how to retain them effectively.

### 🎯 Business Problem
PowerCo is concerned about customer attrition in the SME segment. The primary hypothesis was that churn is driven by **price sensitivity**. My task was to test this hypothesis using data science and build a predictive model to identify at-risk customers.

---

## 🛠️ Key Tasks & Achievements

### 1. Business Understanding & EDA
* Analyzed customer and pricing data to identify key trends.
* **Key Insight:** Rejected the initial hypothesis; data showed that price sensitivity is *not* the primary driver of churn.
* Performed deep-dive visualizations using **Matplotlib** and **Seaborn**.

### 2. Feature Engineering
* Developed new features, including price differences between periods and tenure-based metrics.
* Applied **Log Transformations** to handle skewed consumption data.
* Encoded categorical variables for machine learning compatibility.

### 3. Predictive Modeling (Random Forest)
* Built and optimized a **Random Forest Classifier**.
* Achieved a **50% Recall rate** through strategic class weight balancing, ensuring the model identifies half of the potential churners (a 3x improvement over random guessing).
* Evaluated performance using Precision, Recall, and F1-Score.

### 4. Strategic Communication
* Synthesized technical findings into a concise **Executive Summary** for stakeholders.
* Delivered actionable recommendations: shifting focus from blanket discounts to targeted retention based on consumption patterns and margins.

---

## 🧪 Skills Learned
* **Programming:** Python (Pandas, NumPy, Scikit-Learn)
* **Data Science:** EDA, Feature Engineering, Random Forest, Model Evaluation.
* **Consulting:** Business Understanding, Hypothesis Testing, Executive Communication.

---

## 📜 Disclaimer
*This project was completed as part of the BCG Data Science Virtual Experience Program on Forage. It is a simulation and does not represent an actual employment relationship with Boston Consulting Group (BCG).*
