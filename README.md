
## Credit Card Financial Report Analysis Dashboard
## Table of Contents

Project Description

The Steps Taken

1. Create a Database

2. Create cc_detail and cust_detail Tables

3. Import CSV Data into SQL

4. Insert Additional Data

Power BI Dashboard

Key SQL Queries

Conclusion
## Project Description

This project involves importing credit card and customer data from CSV files into an SQL database. The data is organized into two tables: cc_detail and cust_detail. These tables contain information regarding credit card transactions, customer demographics, and account information.

The purpose of this project is to cleanly store and manage data for analysis and reporting. A Power BI dashboard was created to visualize key insights derived from the data, such as customer demographics, card usage patterns, and other financial metrics.


## The Steps Taken

1. . Create a Database
The first step in this process was to create a database where the tables cc_detail and cust_detail would reside.

A database was created to organize and hold the data that is being imported from CSV files.

2. Create cc_detail and cust_detail Tables
Two tables were created in the database to store credit card and customer details:

cc_detail: This table contains transaction and card-related details for each customer.

cust_detail: This table contains demographic and personal information of the customers.

Table Definitions:

cc_detail includes columns like Client_Num, Card_Category, Annual_Fees, Activation_30_Days, Customer_Acq_Cost, Credit_Limit, and others.

cust_detail includes columns like Client_Num, Customer_Age, Gender, Dependent_Count, Education_Level, Marital_Status, Income, and Cust_Satisfaction_Score.

3. Import CSV Data into SQL
Once the tables were created, data was imported from CSV files into the cc_detail and cust_detail tables using the COPY command.

The COPY command is used to load data from CSV files into the database. The file path and delimiter (in this case, a comma) were specified to ensure that the data was correctly parsed.

CSV Files:

credit_card.csv: Contains transaction-related data.

customer.csv: Contains customer demographic data.

After importing, the data from the CSV files was validated by querying the tables.

4. Insert Additional Data
To ensure that the data reflects the most up-to-date records, additional data files (cc_add.csv and cust_add.csv) were imported into the respective tables.

The COPY command was used again to load new data into the cc_detail and cust_detail tables.

5. Creating A Power BI Dashboard:

A Power BI dashboard was created to visualize the data imported into the SQL database. The dashboard serves as a tool for decision-making, helping stakeholders analyze trends, patterns, and key insights about customers and credit card usage.

The Power BI dashboard includes the following features:

Customer Demographics: Visualizes customer data, such as age, gender, marital status, income levels, and customer satisfaction score.

Card Usage Patterns: Displays credit card utilization data, including credit limits, total revolving balance, and transaction amounts.

Delinquency Analysis: Identifies and visualizes customers with delinquent accounts.

Trends Over Time: Displays the trend of credit card usage over different weeks and quarters.

Geographic Analysis: Uses data on customer locations to visualize trends by state or zipcode.

This dashboard was built by connecting Power BI to the SQL database, importing the cc_detail and cust_detail tables, and using various Power BI features like charts, tables, and slicers to present the data interactively.
## Conclusion

This project successfully demonstrates the process of importing data from CSV files into an SQL database for further analysis. The tables cc_detail and cust_detail were created and populated with data using the COPY command. Additional data was also inserted into the tables to keep the records up-to-date.

A Power BI dashboard was then created to visualize key insights from this dataset. This includes customer demographics, card usage patterns, and financial metrics such as credit limits and transaction amounts.

This project provides a foundation for building advanced analytical models and interactive reports using SQL and Power BI.