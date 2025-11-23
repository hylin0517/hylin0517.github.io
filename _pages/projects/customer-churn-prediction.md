---
layout: single
title: "Customer Churn Prediction"
permalink: /projects/customer-churn-prediction/
tags: [python, classification, xgboost]
excerpt: "Built a machine learning model to predict customer churn with 87% accuracy using XGBoost."
---

## Overview

Developed a classification model to predict which customers are likely to churn, helping businesses take proactive retention actions.

**Key Results:**
- 87% prediction accuracy
- Identified top 5 churn risk factors
- Trained on 7,000+ customer records

**Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, Matplotlib

**GitHub:** [View Code](https://github.com/hylin0517/AMS317-Group3)

---

## The Problem

A telecommunications company needed to identify at-risk customers before they left. Manual analysis wasn't scalable, and they needed an automated solution.

---

## Approach

1. **Data Cleaning:** Handled missing values and outliers
2. **Feature Engineering:** Created tenure groups, service engagement scores
3. **Modeling:** Tested Logistic Regression, Random Forest, XGBoost
4. **Evaluation:** XGBoost performed best with 87% accuracy

---

## Key Findings

![Feature Importance](/assets/images/churn-feature-importance.png)

**Top churn indicators:**
- Contract type (month-to-month vs annual)
- Customer tenure
- Monthly charges
- Tech support subscription
- Internet service type

---

## Results

- **Accuracy:** 87%
- **Precision:** 79%
- **Recall:** 76%

The model successfully identified 3 out of 4 customers who would churn, enabling targeted retention campaigns.

---

## What I Learned

- Handling imbalanced datasets with SMOTE
- Feature importance analysis for business insights
- Hyperparameter tuning with GridSearchCV
- Translating technical results into business value
