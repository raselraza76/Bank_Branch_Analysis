# 🏦 Bank Branch Performance Analysis | Power BI

A Power BI dashboard built to analyze bank branch performance across deposits, loans, revenue, expenses, NPA, and customer activity. The project helps compare branches and regions and understand how performance changes over time.

## 📊 Project Overview
![Bank Branch Analysis](https://raw.githubusercontent.com/raselraza76/Bank_Branch_Analysis/main/bank_branch_Analysis.png)

This project uses monthly branch-level data to understand the financial and operational performance of different bank branches.

The dashboard focuses on:

* Deposit and loan performance
* Revenue and expenses
* NPA (Non-Performing Assets)
* New and closed customers
* Branch and regional performance
* Monthly performance trends

## 🎯 Business Questions

* Which branches generate the highest revenue?
* Which branches have the highest deposits and loans?
* How are revenue and expenses changing over time?
* Which branches have higher NPA amounts?
* Which branches are gaining the most new customers?
* How does performance differ across regions?
* Which branches are performing better financially?

## 📌 Key Metrics

* Total Deposits
* Total Loans
* NPA Amount
* Revenue
* Expense
* Profit
* New Customers
* Closed Customers
* Customer Net Growth
* Branch Performance

## 🗂️ Dataset

The project contains three tables:

### `Fact_BranchPerformance`

Monthly performance data for each branch.

**Columns:**

* Date
* Branch_ID
* Total_Deposits
* Total_Loans
* NPA_Amount
* Revenue
* Expense
* New_Customers
* Closed_Customers

### `Dim_Branch`

Branch-related information.

**Columns:**

* Branch_ID
* Branch_Name
* City
* State
* Region
* Branch_Manager

### `Dim_Date`

Date dimension used for time-based analysis.

**Columns:**

* Date
* Year
* Quarter
* Month
* Month_Name
* Week
* Day

## 🔗 Data Model

The project follows a simple **Star Schema** approach.

```text
                 Dim_Date
                    │
                    │
                    ▼
          Fact_BranchPerformance
                    ▲
                    │
                    │
               Dim_Branch
```

`Branch_ID` connects the branch dimension with the performance fact table, while `Date` is used for time-based analysis.

## 🛠️ Tools Used

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Excel**
* **Data Visualization**

## 📈 Dashboard Analysis

### Branch Performance

Compare branches based on:

* Deposits
* Loans
* Revenue
* Expenses
* Profit
* NPA

### Financial Analysis

Analyze:

* Revenue trends
* Expense trends
* Profit performance
* Deposit growth
* Loan portfolio

### Customer Analysis

Track:

* New customers
* Closed customers
* Net customer growth
* Branch-wise customer performance

### Regional Analysis

Compare branch performance across:

* North
* South
* East
* West

### Time Analysis

Analyze monthly and quarterly trends to identify changes in branch performance throughout the year.

## 💡 Key Insights

The dashboard makes it easier to identify:

* High-performing and underperforming branches
* Branches with strong deposit and loan portfolios
* Areas with relatively high NPA
* Revenue and expense patterns
* Customer acquisition and retention trends
* Differences in performance between regions

## 🎓 Skills Demonstrated

* Data cleaning
* Data transformation
* Power Query
* DAX
* Data modeling
* Star schema
* KPI development
* Financial analysis
* Branch performance analysis
* Customer analysis
* Time-series analysis
* Interactive dashboard development

## 🔗 Live Dashboard

🚀 **[View Interactive Power BI Dashboard](https://app.powerbi.com/links/Op2lwFRJFG?ctid=f438d128-033e-45cd-8dde-1ffdce68e24c&pbi_source=linkShare)**


## 👨‍💻 About the Project

I created this project to practice analyzing business data with Power BI and to understand how financial and operational data can be turned into useful insights for decision-making.

---

