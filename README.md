# 💳 Credit Card Financial Report Analysis Dashboard

## 📚 Table of Contents
1. [Project Description](#project-description)
2. [The Steps Taken](#the-steps-taken)
    1. [Create a Database](#create-a-database)
    2. [Create cc_detail and cust_detail Tables](#create-cc_detail-and-cust_detail-tables)
    3. [Import CSV Data into SQL](#import-csv-data-into-sql)
    4. [Insert Additional Data](#insert-additional-data)
    5. [Power BI Dashboard](#power-bi-dashboard)
3. [Key SQL Insights](#key-sql-insights)
4. [Conclusion](#conclusion)

## 📝 Project Description
This project focuses on analyzing credit card usage and customer demographics through a well-structured SQL database, with the final output being an interactive Power BI Dashboard. The data comes from two primary CSV files, each containing essential information regarding customer profiles and credit card transactions.

### Objective:
To manage and analyze customer and credit card transaction data for insightful reporting and analysis. The project provides insights into customer behavior, financial metrics, and credit card activity trends, ultimately helping stakeholders make informed decisions.

### Primary Tables:
- **cc_detail**: Contains credit card transaction data, including:
  - `Client_Num`
  - `Card_Category`
  - `Annual_Fees`
  - `Activation_30_Days`
  - `Customer_Acq_Cost`
  - `Credit_Limit`

- **cust_detail**: Contains customer demographic and account information, including:
  - `Client_Num`
  - `Customer_Age`
  - `Gender`
  - `Dependent_Count`
  - `Education_Level`
  - `Marital_Status`
  - `Income`
  - `Cust_Satisfaction_Score`

## 🛠 The Steps Taken

### 📂 Create a Database
A dedicated database was created to securely store and manage both customer and credit card transaction data. This ensures that all data is centrally located and easily accessible for reporting and analysis.

### 🧾 Create cc_detail and cust_detail Tables
The two primary tables were created using SQL:

- **cc_detail**: Stores all credit card-related information.
- **cust_detail**: Stores customer demographic details.

The table structures were designed to support the analysis of credit card usage and customer behavior efficiently.

### 📥 Import CSV Data into SQL
The following CSV files were imported into the SQL database:

- `credit_card.csv` → Populated the `cc_detail` table.
- `customer.csv` → Populated the `cust_detail` table.

The `COPY` command was used for importing data, ensuring smooth parsing of delimiters and validating the imported data for consistency and accuracy.

### ➕ Insert Additional Data
Additional datasets were imported to ensure that the database remains up-to-date with the latest information:

- `cc_add.csv` → Updated the `cc_detail` table.
- `cust_add.csv` → Updated the `cust_detail` table.

### 📊 Power BI Dashboard
An interactive Power BI Dashboard was developed to provide dynamic, visually compelling reports. Key visualizations include:

- **Customer Demographics**:
  - Age, Gender, Marital Status, Income Bracket, Satisfaction Scores.

- **Card Usage Patterns**:
  - Credit Limits, Total Revolving Balance, Activation Status, Annual Fees.

- **Delinquency Analysis**:
  - Identifying accounts with missed payments or risk flags.

- **Trends Over Time**:
  - Weekly and quarterly usage analysis for spending and engagement trends.

- **Geographic Analysis**:
  - State- or Zipcode-based customer concentration and usage behavior.

Power BI features such as bar charts, pie charts, slicers, filters, and geographic maps were employed to present the data in an engaging way.

## 🔍 Key SQL Insights
- **Top Income Customers with High Credit Limits**:
  - Identify customers with high incomes and credit limits to understand the segment with the greatest financial potential.

- **Tracking Delinquency Over Time**:
  - Track customer delinquency and missed payments over time to identify patterns and high-risk customers.

- **Customer Demographics with Credit Usage**:
  - Analyze how various customer demographics, such as age or marital status, correlate with their credit card usage.

- **Card Category Usage by Region or Income Level**:
  - Aggregate credit card usage by region or income level to determine trends and tailor marketing efforts accordingly.

## ✅ Conclusion
This project effectively demonstrates a comprehensive data analysis workflow involving:

- Structured data management using SQL with the creation of `cc_detail` and `cust_detail` tables.
- Data ingestion through the importation of primary and additional datasets via CSV.
- Interactive reporting through the development of a Power BI dashboard to visualize trends and insights.

The project provides valuable insights into customer behavior, credit utilization patterns, and risk profiling, which can be leveraged for targeted financial strategies and decision-making. This solution sets the stage for more advanced financial analytics and customer relationship management.
