# Credit Card Financial Dashboard

## 📊 Project Overview

The Credit Card Financial Dashboard is an interactive Business Intelligence project developed to analyze credit card transactions and customer information.

The project uses PostgreSQL and SQL for data storage and preparation, while Power BI is used to build an interactive dashboard with DAX measures and calculated columns.

The dashboard provides insights into revenue, transaction activity, customer demographics, card categories, expenditure types, income, and other customer-related metrics.

---

## 🎯 Project Objective

The main objective of this project is to transform credit card and customer data into meaningful business insights through SQL, PostgreSQL, Power BI, and DAX.

The dashboard helps analyze:

- Credit card transaction performance
- Revenue trends
- Transaction volume
- Customer demographics
- Customer income and salary groups
- Card categories
- Expenditure types
- Customer job categories
- Education levels
- Gender distribution
- Age groups
- Geographic distribution
- Monthly and quarterly performance

---

## 🗂️ Dataset

The project uses four CSV files:

- `credit_card.csv`
- `cc_add.csv`
- `customer.csv`
- `cust_add.csv`

The additional datasets were used to append additional records to the main datasets.

### Data Structure

The project contains two main data tables:

- `cc_detail` – Credit card transaction details
- `cust_detail` – Customer details

`Client_Num` is used as the common customer identifier between the datasets.

---

## 🛠️ Technologies Used

- **PostgreSQL**
- **SQL**
- **Power BI**
- **DAX**
- **CSV**
- **Power BI Data Modeling**

---

## 🔄 Project Workflow

```text
CSV Files
    ↓
PostgreSQL Database
    ↓
Data Tables
    ↓
SQL Data Preparation
    ↓
Power BI Connection
    ↓
Data Modeling
    ↓
DAX Measures & Calculated Columns
    ↓
Interactive Power BI Dashboard
