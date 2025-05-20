# Invoice-Fraud-Detection
A project combining rule-based logic and machine learning to flag suspicious invoices, supported with a Power BI dashboard.

## Project Objectives

Detect potential invoice fraud using logic-based and ML-based methods
Create meaningful features that reflect business patterns (e.g., delivery delay, credit vs. amount ratio)
Visualize anomalies and risk areas across regions, dates, and currencies
Help finance teams reduce manual review time and identify red flags early

 ## Data Overview

**Source**: Combination of publicly available Kaggle invoice data and synthetic records
**Size**: 1.1M+ invoices
**Fields**: Order ID, customer, amount, currency, creation date, credit released, delivery date, and more
**Note**: No sensitive or proprietary data is used

## Tools and Technologies

**Python**: pandas, scikit-learn, matplotlib
**Power BI**: for dashboarding and interactive filtering
**Machine Learning**: Isolation Forest for unsupervised anomaly detection
**Rule Logic**: 7 custom rules (e.g., duplicate invoice, zero amount with credit, outlier detection)

![image](https://github.com/user-attachments/assets/867eb819-9140-423d-830a-b5e4e6ea243b)

## Key Features

Flags duplicate, outlier, and suspicious invoices
Combines 7 rule-based checks with a machine learning model
Interactive filters by date, currency, region, and vendor
Shows fraud trends over time and by business unit

## Dashboard Preview

![image](https://github.com/user-attachments/assets/a12653b0-efa1-4eee-a9ae-3ccde287a2fa)

![image](https://github.com/user-attachments/assets/bab86c29-2f36-4a57-b77a-2c9735ebd11c)

