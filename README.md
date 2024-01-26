<img width="633" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/c0813068-8776-4a8b-ac72-7e630be758d5"># KPMG-Virtual-Data-Analyst-intern-project
This project is aimed at identifying all data quality issues, and developing a dash board to showcase the 1000 target customers.

![image](https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/327c8ece-14b1-4ee9-8529-58bce5c0f9ff)

# Introduction

I applied to Forage to participate in the KPMG Data Analyst Intership program. In this project, Sprocket Central Pty Ltd has approached KPMG with their transaction data, customer demographic data and customer address data set to effectively analyse and provide professional advice on how best to optimise its marketing strategy.
For this, I have being required to fulfill a range of tasks that align with the responsibilities typically assigned to a data analyst in a professional setting. Throughout this program, I successfully completed three stages of tasks.

1. Data Quality Assessment
2. Data Exploration
3. Data insight/visualization

Data quality assessment involves evaluating the reliability, accuracy, consistency, and completeness of data. It aims to ensure that the data used for analysis, reporting, or decision-making is trustworthy and meets certain standards. I used the Power query for the Data Quality assessment, I was able to identify the following.

# Customer Address Data Quality assessment
Customer Addresses table contains "customer_id", "address", "postcode", "state", "country", "property_valuation"

The values are consistent, with no empty row or error in the relevant columns. I removed the empty columns that were present when the dataset was imported into power BI.

<img width="636" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/1e89a92c-2d6a-45df-90b1-3b754505712e">

# Transaction Data quality assessment 
The Transactions table encompasses "transaction_id", "product_id", "customer_id", "transaction_date", "online_order", "order_status", "brand", "product_line", "product_class", "product_size", "list_price", "standard_cost", "product_first_sold_date"

The columns below has inconsistent values, with empty rows.
<img width="633" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/7b82f31e-833a-40ce-91fc-8e3caee9d3ac">

<img width="609" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/e9799e6c-e47a-4d96-8fc5-4375968dc6e1">




