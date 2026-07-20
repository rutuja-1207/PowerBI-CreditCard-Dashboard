# 💳 Credit Card Customer & Transaction Analysis Dashboard

## 📌 Project Overview

This project analyzes customer information and credit card transaction data using Power BI.

The main objective is to understand customer behavior, revenue trends, transaction patterns, and generate business insights to support decision-making.

---

## 🎯 Business Problem

Banks generate large amounts of customer and transaction data every day.

It is difficult to identify:
- High-value customers
- Revenue trends
- Spending patterns
- Customer segments
- Business performance

---

## 💡 Solution

I developed an interactive Power BI dashboard to analyze customer and transaction data.

The dashboard helps businesses monitor KPIs, customer behavior, revenue performance, and make data-driven decisions.

---

## 🛠 Tools Used

- Power BI
- PostgreSQL
- Power Query
- DAX

---

## 🗂 Data Source

The project uses two datasets:

- customer.csv
- credit_card.csv

Both tables are connected using **Client_Num**.

---

## 🔗 Data Modeling

Relationship:

**Customer Table (1) → Credit Card Table (Many)**

Primary Key:

**Client_Num**

---

## 🧹 Data Cleaning

Performed using Power Query.

- Removed null values
- Removed duplicate records
- Changed data types
- Created Age Group
- Created Income Group

---

## 🧮 DAX Measures

- Current Week Revenue
- Previous Week Revenue
- Week over Week Revenue
- Age Group
- Income Group

---

## 📊 Dashboard Pages

### 1️⃣ Customer Dashboard

- Customer demographics
- Revenue by Gender
- Revenue by Income
- Revenue by Education
- Revenue by State

---

### 2️⃣ Transaction Dashboard

- Revenue
- Transaction Amount
- Transaction Count
- Interest Earned
- Card Category Analysis

---

### 3️⃣ Insights Dashboard

Business insights and recommendations based on customer and transaction analysis.

---

## 📈 Key Insights

- Customers aged 40–50 generate the highest revenue.
- High-income customers contribute the most revenue.
- Blue Card category performs best.
- Swipe is the preferred transaction method.
- Revenue remains consistent across quarters.

---

## 💼 Business Recommendations

- Focus marketing on high-income customers.
- Improve offers for low-performing customer segments.
- Increase digital payment adoption.
- Strengthen Blue Card benefits.

---

## 📂 Project Structure

PowerBI-CreditCard-Dashboard

├── README.md

├── final pro.pbix

├── Dataset

├── Dashboard Images

├── Documentation

└── DAX Measures

---

## 🖼 Dashboard Screenshots

### Customer Dashboard

(Add Screenshot)

### Transaction Dashboard

(Add Screenshot)

### Insights Dashboard

(Add Screenshot)

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX
- Dashboard Design
- Business Analysis
- Data Visualization

---

## 📌 Conclusion

This project helped me understand how to convert raw data into meaningful insights and support business decision-making using Power BI.
