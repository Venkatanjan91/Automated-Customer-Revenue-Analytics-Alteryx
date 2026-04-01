# 📊 Automated Customer Revenue Analytics (Alteryx Workflow)

## 🔍 Project Overview
This project presents a fully automated data analytics workflow built using Alteryx to analyze customer purchasing behavior and generate key revenue insights. The workflow integrates multiple datasets, performs data transformation, and derives business-critical metrics for decision-making.

---

## 🎯 Objective
The goal of this project is to:
- Combine customer and transaction datasets  
- Calculate key performance metrics  
- Identify high-value customers  
- Deliver a structured dataset ready for reporting and visualization  

---

## 🗂️ Data Sources
- **Customers.xlsx**  
  Contains customer details such as Customer ID and attributes  

- **Transactions.xlsx**  
  Contains transaction-level data including purchase amounts and frequency  

---

## ⚙️ Workflow Steps

### 1. Data Input
- Import datasets using Alteryx Input tools  

### 2. Data Preparation
- Clean and standardize data  
- Ensure consistent data types  

### 3. Data Blending
- Join customer and transaction data using a common key  
- Ensures accurate mapping of transactions to customers  

### 4. Data Aggregation
- Calculate:
  - Total Spend per customer  
  - Number of Transactions  

### 5. Feature Engineering
- Compute:
  - Average Spend = Total Spend / Number of Transactions  
- Handle edge cases (e.g., division by zero)  

### 6. Sorting & Ranking
- Sort customers by Total Spend (Descending)  
- Identify top revenue-generating customers  

### 7. Output Generation
- Export final dataset in `.yxdb` format for further analysis  

---

## WorkFlow

<img width="1275" height="319" alt="Screenshot 2026-04-01 150851" src="https://github.com/user-attachments/assets/36d21065-d83d-48bd-99cd-6736dcbe411a" />

---

## 📈 Key Metrics
- Total Customer Spend  
- Average Spend per Transaction  
- Customer Ranking by Revenue  

---

## 🛠️ Tools & Technologies
- Alteryx Designer  
- Microsoft Excel  
- Alteryx Database (.yxdb)  

---

## 🚀 Use Cases
- Customer segmentation  
- Identifying high-value customers  
- Revenue optimization strategies  
- Business intelligence and dashboarding  

---


## 👤 Author
**Venkat Anjan Kumar**  
Aspiring Business Analyst | Data Analytics Enthusiast  

---

## ⭐ Support
If you found this project useful, feel free to star ⭐ the repository and fork it!
