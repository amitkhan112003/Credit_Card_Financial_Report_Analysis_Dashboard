
## 💳 Credit Card Financial Report Analysis Dashboard
## 📚 Table of Contents

📝 Project Description

🛠 The Steps Taken

📂 Create a Database

🧾 Create cc_detail and cust_detail Tables

📥 Import CSV Data into SQL

➕ Insert Additional Data

📊 Power BI Dashboard

🔍 Key SQL Queries

✅ Conclusion
## 📝 Project Description

This project focuses on analyzing credit card usage and customer demographics by importing data from CSV files into an SQL database. Two primary tables were created:

cc_detail: Contains credit card transaction and product-related data.

cust_detail: Contains customer demographic and account information.

The aim is to manage this data effectively for reporting and analysis. A Power BI Dashboard was developed to visualize trends in credit card activity, customer behavior, and financial metrics, helping stakeholders gain actionable insights.
## 🛠 The Steps Taken

📂 Create a Database
A dedicated database was created to store and manage customer and credit card transaction data securely.

🧾 Create cc_detail and cust_detail Tables
cc_detail: Stores credit card-related information such as:

Client_Num

Card_Category

Annual_Fees

Activation_30_Days

Customer_Acq_Cost

Credit_Limit

cust_detail: Stores customer demographic details such as:

Client_Num

Customer_Age

Gender

Dependent_Count

Education_Level

Marital_Status

Income

Cust_Satisfaction_Score

📥 Import CSV Data into SQL
Data from two primary CSV files were imported using the COPY command:

credit_card.csv → cc_detail

customer.csv → cust_detail

The data was parsed with appropriate delimiters and validated using SQL queries to ensure consistency and accuracy.

➕ Insert Additional Data
Additional records from:

cc_add.csv

cust_add.csv

were imported using the COPY command to update both tables with the latest data.

📊 Power BI Dashboard
A Power BI Dashboard was created to connect to the SQL database and provide dynamic, interactive reports. Key visualizations include:

👥 Customer Demographics
Age, Gender, Marital Status, Income Bracket, Satisfaction Scores.

💳 Card Usage Patterns
Credit Limits, Total Revolving Balance, Activation Status, Annual Fees.

🚨 Delinquency Analysis
Identifying accounts with missed payments or risk flags.

📈 Trends Over Time
Weekly and quarterly usage analysis for spending and engagement trends.

🗺️ Geographic Analysis
State- or Zipcode-based customer concentration and usage behavior.

The dashboard leverages Power BI features like bar charts, pie charts, slicers, filters, and maps for enhanced storytelling.
## 🔍 Key SQL Queries

Identify top income customers with high credit limits

Track customers with delinquency over time

Join and filter demographics with credit usage

Aggregate card category usage by region or income level
## ✅ Conclusion

This project effectively demonstrates the complete workflow of data ingestion, storage, and visualization:

🧩 Structured data in cc_detail and cust_detail using SQL.

📥 Imported primary and additional datasets via CSV.

📊 Built an interactive Power BI dashboard for analysis.

This solution enables deeper insight into customer behaviors, credit utilization patterns, and risk profiling, laying the groundwork for advanced financial analytics and targeted customer strategies.

