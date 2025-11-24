# 📊 E-Commerce Public Dataset Analysis

Insight-Driven Data Analytics Project

This repository contains an end-to-end exploratory data analysis (EDA) project using a public e-commerce dataset. The notebook walks through data wrangling, assessment, exploratory analysis, visualization, and insights generation to answer key business questions related to customer payments and review behaviors.

## 🧠 Business Questions

This project focuses on answering two core analytical questions:

1. **Which payment methods are most frequently used across different product price ranges?**
2. **How long does it typically take for customers to leave a review after receiving their order?**

---

## 📦 Dataset Overview

The analysis uses three primary datasets:

* **payment_df** – Customer payment information
* **review_df** – Customer review details
* **order_df** – Customer order records

Each dataset undergoes gathering, validation, data type checking, missing value detection, and descriptive statistical analysis.

---

## 🔧 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Wrangling

Steps covered:

### 1. Gathering

Uploading all datasets into the notebook environment.

### 2. Assessing

* Checking data types
* Detecting duplicates
* Inspecting missing values
* Descriptive statistics per dataset

### 3. Cleaning

* Converting columns into appropriate types
* Handling duplicates
* Dealing with missing values
* Adding engineered features where needed

---

## 🔍 Exploratory Data Analysis (EDA)

### **Payment Data Exploration**

Insights include:

* Dominance of specific payment methods
* Spending patterns across price ranges
* Relationship between installment choices and transaction value

### **Review Data Exploration**

Insights include:

* Distribution of review scores
* Review response time
* Customer behavior patterns in leaving reviews

### **Order Data Exploration**

Insights include:

* Order volume
* Delivery time distribution
* Trends in order processing and logistics behavior

---

## 📈 Key Findings

### **1. Payment Method vs Product Price**

* **Credit card payments dominate**, especially for higher-value products.
* Installment-based transactions show a clear pattern:

  > More installments → Higher total transaction value.
* Rare payment methods show near-zero usage, indicating potential data sparsity.

### **2. Customer Review Delay**

* Most customers leave a review **within 0–1 day** after receiving their order.
* This likely reflects strong platform nudging (notifications, incentives).
* Very late reviews (weeks later) are outliers and occur rarely.

---

## 📝 Conclusion

The analysis highlights clear behavioral patterns:

* Customers prefer flexible payments for higher-priced items, particularly credit card installments.
* The review ecosystem functions efficiently, with most customers responding quickly, indicating good platform engagement.

These insights can support feature optimization, marketing strategies, payment options expansion, and customer experience improvements.

---

## 📁 Repository Structure

```
├── notebook.ipynb     # Main analysis notebook
├── README.md          # Documentation
└── data/              # (Optional) Place datasets here if shared
```

---

## 🙌 Author

**Maulidina Rahmawati**
Dicoding ID: MC009D5X2352
