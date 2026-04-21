# Credit Card Fraud Detection Analysis

## Live Dashboard  
https://lookerstudio.google.com/reporting/5248f39c-e466-4a49-a673-39fe7b5a1632  

---

## Project Overview  
This project analyzes credit card transaction data to identify fraud patterns, risky categories, and customer behavior.  

An interactive dashboard is created using Looker Studio to visualize fraud trends across categories, age groups, gender, merchants, and locations.  

The main goal is to help businesses detect fraud early, reduce financial losses, and make better decisions using data.  

---

## Workflow  
1. Data Collection  
2. Data Cleaning and Preprocessing  
3. Feature Engineering  
4. Exploratory Data Analysis (EDA)  
5. Data Visualization using Looker Studio  
6. Insights and Reporting  

---

## Key Objectives  
- Identify fraudulent transaction patterns  
- Analyze fraud distribution across categories  
- Understand customer demographics involved in fraud  
- Detect high-risk merchants and regions  
- Evaluate the financial impact of fraud  

---

## Project Structure  
Credit-Card-Fraud-Detection-Analysis
│
├── data
│ └── cleaned_looker_data_v2.csv
│
├── dashboards
│ └── Looker Studio Dashboard
│
├── images
│ └── dashboard screenshots
│
├── README.md
└── analysis files

---

## Data Dictionary  

- trans_date → Transaction date  
- amt → Transaction amount  
- category → Transaction category  
- gender → Customer gender  
- age → Customer age  
- merchant → Merchant name  
- city → Customer city  
- is_fraud → Fraud flag (0 = No, 1 = Yes)  

---

## Data Summary  

- Total Transactions: 174,531  
- Total Amount: 12.3M+  
- Unique Customers: 928  
- Unique Merchants: 693  
- Unique Cities: 892  

---

## Fraud Classification  

- 0 → Legitimate Transaction  
- 1 → Fraudulent Transaction  

---

## Financial Overview  

- Total transaction value exceeds 12M+  
- Fraud contributes significantly to financial risk  
- Spending patterns vary across categories  

---

## Category Distribution  

- Grocery, shopping, and travel dominate transaction volume  
- Fraud distribution differs across categories, showing targeted fraud behavior  

---

## Dashboard Overview  

### Page 1: Transaction & Fraud Summary  

<img src="Dashboard/Screenshot%202026-04-07%20000129.png" width="100%">


**Description:**  
This page provides a high-level overview of all transactions and fraud activity.  

**Key Highlights:**  
- Total transactions and total transaction amount  
- Overall fraud vs non-fraud comparison  
- Category-wise transaction distribution  
- Quick insights into fraud concentration  

---

### Page 2: Customer Demographics Analysis  

<img src="Dashboard/Screenshot%202026-04-07%20000249.png" width="100%">


**Description:**  
This page focuses on customer behavior and demographic insights related to fraud.  

**Key Highlights:**  
- Fraud distribution by age group  
- Gender-based fraud comparison  
- Identification of high-risk customer segments  
- Behavioral trends across different demographics  

---

### Page 3: Merchant & Location Analysis  

<img src="Dashboard/Screenshot%202026-04-07%20000220.png" width="100%">


**Description:**  
This page highlights fraud patterns across merchants and geographic regions.  

**Key Highlights:**  
- High-risk merchants associated with fraud  
- City-wise fraud distribution  
- Detection of fraud hotspots  
- Regional trends in fraudulent transactions  

---

## Workflow  
1. Data Collection  
2. Data Cleaning and Preprocessing  
3. Feature Engineering  
4. Exploratory Data Analysis (EDA)  
5. Data Visualization using Looker Studio  
6. Insights and Reporting  

---

## Tools Used  

- Looker Studio  
- CSV Dataset  
- Excel / Python (for preprocessing)  

---

## Conclusion  

This project demonstrates how data analysis and visualization can help detect fraud patterns and support better financial decision-making.

---
##  Future Enhancements
- Implement Machine Learning models (Logistic Regression, Random Forest, XGBoost)  
- Build a real-time fraud detection system  
- Deploy the project as a web application  
- Integrate anomaly detection techniques  
- Add automated alert system for suspicious transactions  
- Deploy on cloud platforms (AWS / GCP) 
