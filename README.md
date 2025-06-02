# Credit-Card-Fraud-Detection
# Credit Card Fraud Detection

This project was completed as part of the CIS 9557 course on Business Analytics. It aims to detect fraudulent transactions using machine learning on a highly imbalanced dataset.

## Overview

We analyzed a dataset of 284,807 credit card transactions, with only 0.17% labeled as fraud. Our goal was to improve fraud detection accuracy while minimizing false positives, using techniques like:

- SMOTE (Synthetic Minority Oversampling)
- XGBoost & Random Forest Classifiers
- Threshold Tuning & Confusion Matrix Analysis
- Temporal and behavioral feature insights

## Key Insights

- Most fraud occurred between **12pm–6pm**, not at night
- Fraudulent transactions were typically **under $200**
- **XGBoost** performed best with the highest F1-score

## Tools Used

- Python (Google Colab)
- Scikit-learn, XGBoost, SMOTE
- Matplotlib, Seaborn
- Business process risk analysis

## Files

- [`Credit_Card.ipynb`](Credit_Card.ipynb) – Main Python notebook
- [`Group 1 - Final Project Report.pdf`] (Credit%20Card%20Final%20Project%20Report.pdf)) – Full report
- [`Group-1 Presentation.pdf`](Credit%20Card%20Presentation.pdf) – Slide deck

## POAM Highlights

We proposed a Plan of Action & Milestones (POAM) focused on:
- Real-time fraud scoring
- Risk-level based threshold adjustment
- Monitoring high-risk time periods

