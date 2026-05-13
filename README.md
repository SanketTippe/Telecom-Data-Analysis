# TELECOM CUSTOMER & REVENUE ANALYTICS

## Project Overview
This project focuses on analyzing Telecom Customer and Revenue data using Power BI. The dashboard provides insights into customer behavior, revenue generation, data usage, recharge patterns, and customer support issues.

The main objective of this project is to help telecom companies understand customer trends, improve service quality, and increase revenue through data-driven decisions.

---

# Tools & Technologies Used

- Power BI
- Microsoft Excel
- SQL
- DAX
- Data Visualization

---

# Dataset Information

The dataset contains telecom customer details, recharge history, usage statistics, and customer support issues.

## Tables Used

### 1. CustomerMaster
Contains customer information:
- Customer ID
- Customer Name
- Gender
- City
- State
- Plan Type
- Status

### 2. RechargeHistory
Contains recharge details:
- Recharge Amount
- Recharge Date
- Revenue
- Plan Details

### 3. UsageData
Contains customer usage details:
- Data Usage (GB)
- Call Usage
- SMS Usage

### 4. SupportTickets
Contains support issue details:
- Issue Type
- Ticket Status
- Resolved/Unresolved Issues

---

# Dashboard Pages

## 1. Overview Dashboard

### KPIs
- Total Customers
- Total Revenue
- Total Data Usage
- Popular Plan

### Visuals
- Customer by City
- Data Usage by City
- Customer by Gender
- Postpaid vs Prepaid Revenue

### Filters
- City
- State
- Gender

---

## 2. Customer & Issues Dashboard

### KPIs & Insights
- Top Data Usage Month
- Highest Revenue City
- Top 3 Customers
- Top 10 Customers
- Customer Issues
- Unresolved Issues by City
- Total Issues by Type
- Customers with High Data Usage & Issues

---

## 3. Support Dashboard
This dashboard focuses on support ticket analysis and issue tracking.

### Visuals
- Open vs Resolved Tickets
- Issue Categories
- Resolution Analysis
- City-wise Issues

---

# Business Insights

- Pune generated the highest revenue.
- August had the highest data usage.
- Postpaid users generated slightly higher revenue than prepaid users.
- Network and Recharge issues were the most common customer complaints.
- High data usage customers contribute more to telecom revenue.

---

# Key Features

- Interactive Power BI Dashboard
- Dynamic Filters & Slicers
- KPI Cards
- Revenue Analysis
- Customer Insights
- Telecom Usage Analytics
- Support Issue Tracking

---

# Power BI Features Used

- KPI Cards
- Bar Charts
- Donut Charts
- Tables
- Slicers
- Navigation Buttons
- DAX Measures
- Data Modeling

---

# Project Objectives

- Analyze customer demographics
- Track telecom revenue
- Monitor customer usage trends
- Analyze customer complaints
- Generate business insights
- Improve customer experience

---

# Conclusion

This Telecom Customer & Revenue Analytics project helps telecom companies understand customer behavior, revenue trends, and support issues using interactive Power BI dashboards. The project demonstrates data visualization, business intelligence, and analytical skills.

---

# Future Improvements

- Customer Churn Prediction
- Machine Learning Integration
- Real-Time Dashboard
- Revenue Forecasting
- Advanced DAX Calculations

---

# Author

**Sanket Tippe**

---

# GitHub Repository Structure

```bash
Telecom-Customer-Revenue-Analytics/
│
├── Telecom_Dataset.xlsx
├── telecom.pbix
├── README.md
└── screenshots/
-----

# SQL Sample Queries

## Total Customers
```sql
SELECT COUNT(*) AS TotalCustomers
FROM CustomerMaster;

## Total Revenue
SELECT SUM(Amount) AS TotalRevenue
FROM RechargeHistory;






