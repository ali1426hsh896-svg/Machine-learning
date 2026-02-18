# Lab 3: Exploratory Data Analysis (EDA)

**Course:** ARTI308 - Machine Learning

---

## Overview

This lab applies EDA techniques on a customer purchase dataset to understand the data, find patterns, and extract insights before building any machine learning model.

---

## Dataset Features

| Column | Description |
|---|---|
| `CustomerID` | Unique identifier for each customer |
| `Age` | Customer age (18 – 70) |
| `Gender` | Male / Female |
| `Location` | Customer country (USA, UK, Canada, Germany, India, Australia) |
| `ProductCategory` | Books, Sports, Clothing, Home, Electronics |
| `PurchaseAmount` | Total purchase value in USD |
| `PaymentMethod` | PayPal, Cash, Debit Card, Credit Card |
| `PurchaseDate` | Date of the transaction |
| `DeviceUsed` | Desktop, Mobile, Tablet |
| `ReturningCustomer` | Whether the customer purchased before (Yes / No) |

---

## EDA Techniques

- **Missing Value Analysis** — checking for null values using `isna()`
- **Duplicate Detection** — identifying repeated rows
- **Descriptive Statistics** — summary of mean, min, max, and std
- **Univariate Analysis** — histograms for Age and Purchase Amount
- **Bivariate Analysis** — bar charts comparing amount by Location, Category, and Payment Method
- **Correlation Matrix** — heatmap between Age and Purchase Amount
- **Time-Based Analysis** — monthly purchase trend over 2024–2025

---

## Key Findings

- No missing or duplicate values — the dataset is clean
- Average purchase amount is **~$1,042** (range: $54 – $1,997)
- **Mobile** is the most used device (172 out of 500 transactions)
- **Debit Card** is the most common payment method
- **Home** is the top product category with 107 purchases
- **51.4%** of customers are new, indicating room for retention improvement
- Gender is nearly balanced — 253 Male, 247 Female

---

*ARTI308 - Machine Learning | Lab 3*
