# Dataset Description - Customer Purchase Dataset

## Overview
This dataset contains customer transaction records from an e-commerce platform with **501 records** and **10 features**. It is designed to predict customer retention behavior using demographic and purchasing information.

---

## Dataset Information
- **Format:** CSV
- **Records:** 501 transactions
- **Features:** 10 columns
- **Missing Values:** None
- **Target Variable:** ReturningCustomer (Yes/No)

---

## Features

| Feature | Type | Description | Values/Range |
|---------|------|-------------|--------------|
| **CustomerID** | String | Unique customer identifier | UUID format |
| **Age** | Numerical | Customer age | 18-70 years |
| **Gender** | Categorical | Customer gender | Male, Female |
| **Location** | Categorical | Customer country | USA, UK, Canada, Germany, India, Australia |
| **ProductCategory** | Categorical | Product type purchased | Books, Sports, Clothing, Home, Electronics |
| **PurchaseAmount** | Numerical | Transaction value | $50 - $2000 (approx.) |
| **PaymentMethod** | Categorical | Payment type | Credit Card, Debit Card, PayPal, Cash |
| **PurchaseDate** | Date | Transaction date | 2024-2025 |
| **DeviceUsed** | Categorical | Shopping device | Desktop, Mobile, Tablet |
| **ReturningCustomer** | Categorical (Target) | Customer status | **Yes** (returning), **No** (new) |

---

## Machine Learning Problem

**Problem Type:** Binary Classification

**Objective:** Predict whether a customer will return for future purchases based on their demographic and purchase characteristics.

**Independent Variables:** Age, Gender, Location, ProductCategory, PurchaseAmount, PaymentMethod, PurchaseDate, DeviceUsed

**Dependent Variable (Target):** ReturningCustomer

---

## Sample Data

| Age | Gender | Location | ProductCategory | PurchaseAmount | ReturningCustomer |
|-----|--------|----------|-----------------|----------------|-------------------|
| 38 | Male | Germany | Books | $1969.04 | Yes |
| 70 | Female | Canada | Sports | $464.76 | No |
| 41 | Male | Australia | Sports | $58.10 | No |

---

## Use Cases
- Predict customer retention likelihood
- Identify factors influencing repeat purchases
- Optimize marketing strategies for customer loyalty
- Segment customers based on behavior patterns

---

## Data Quality
- Complete dataset with no missing values
- Balanced mix of categorical and numerical features
- Suitable for supervised classification tasks
