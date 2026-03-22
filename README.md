# Data-analysis-Business-dataset
# Dataset Overview

##  Introduction

This dataset contains financial transaction records of users, including details about income, expenses, categories, payment methods, and user behavior. The objective of this analysis is to understand spending patterns, identify key expense drivers, and generate insights to support better financial decision-making.

---

##  Dataset Description

The dataset consists of **15,000+ transaction records** with the following features:

* **transaction_id** → Unique identifier for each transaction
* **user_id** → Unique identifier for each user
* **transaction_type** → Indicates whether the transaction is *Income* or *Expense*
* **category** → Type of transaction (e.g., food, rent, utilities, etc.)
* **amount** → Transaction value (cleaned and converted to numeric format)
* **payment_mode** → Method of payment (UPI, card, cash, bank transfer)
* **location** → City/location of transaction
* **notes** → Additional transaction details

---

##  Data Challenges

The dataset required significant preprocessing due to:

* Missing values in multiple columns
* Inconsistent category labels (e.g., "food", "Food", "fod")
* Mixed formats in the `amount` column (currency symbols, text)
* Duplicate transaction records
* Presence of outliers and unrealistic values

---

##  Data Cleaning Summary

To ensure data quality, the following steps were performed:

* Removed duplicate records based on `transaction_id`
* Standardized category and payment mode values
* Cleaned and converted the `amount` column to numeric format
* Handled missing values appropriately
* Removed outliers and anomalous values
* Dropped unreliable columns (e.g., date) due to excessive missing data

---

##  Objective of Analysis

The main goals of this analysis are:

* Analyze income vs expense patterns
* Identify top spending categories
* Understand user behavior and high-value users
* Explore payment method preferences
* Generate insights for financial planning and decision-making

---

