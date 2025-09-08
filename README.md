# ☕ Cafe-Sales-Analysis

## 📌Project Overview
The project analyses a **cafe sales dataset** to extract business insights and **interactive dashboard** in Power BI. The dataset was taken from [kaggle](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training). The dataset was messy and required extensive **data cleaning and preprocessing** before any meaningful insights could be derived.

The goal is to demonstrate complete **data analysis workflow**:
1. **Exploratory Data Analysis (EDA)** - Using descriptive and inferential statistics to understand the dataset
2. **Data Cleaning** - Handling garbage values, handling missing values, logical imputation
3. **Business Insights Dashboard** - Designing a Power BI dashboard for cafe managers to track revenue, items, and customer behaviour

## 📂Dataset Description
### Overview
The Dirty Cafe Sales dataset contains 10,000 rows of synthetic data representing sales transactions in a cafe. This dataset is intentionally "dirty," with missing values, inconsistent data, and errors introduced to provide a realistic scenario for data cleaning and exploratory data analysis (EDA). It can be used to practice cleaning techniques, data wrangling, and feature engineering.
### Column Description
The dataset contains the following columns:
+ `Transaction ID` → Unique identifier for each sale
+  `Item` → Product sold
    - Coffee
    - Cake
    - Cookie
    - Salad
    - Smoothie
    - Sandwich
    - Juice
    - Tea
+ `Quantity` → Number of units purchased
+ `Price Per Unit` → Price of a single item
+ `Total Spent` → Total bill for the transaction
+ `Payment Method` → Mode of Payment
   - Credit Card
   - Cash
   - Digital Wallet
+ `Location` → Sale type
   - Take-away
   - In-store
   - Unknown
+ `Transaction Date` → Date of Transaction

Here, `Quantity`, `Price Per Unit`, and `Total Spent` are numerical type features. `Transaction Date` is DateTime. `Item`, `Payment Method`, and `Location` are categorical.

## 🛠 Data Cleaning & Imputation
+ **Handled missing values** using a mix of **logical imputation** (e.g. `Total = Quantity x Price Per Unit`) and **statistical imputation** (mean/median/mode).
+ **Fixed inconsistent item entries** using mapping and replacement.
+ **Standardized price per unit** across items.
