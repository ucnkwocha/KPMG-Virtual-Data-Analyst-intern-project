# KPMG-Virtual-Data-Analyst-intern-project
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

The values are complete, with no empty row or error in the relevant columns. I removed the empty columns that were present when the dataset was imported into power BI.

<img width="636" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/1e89a92c-2d6a-45df-90b1-3b754505712e">

To ensure consistency in the state column, i replaced "North south wales" with "NSW " and i also replaced "Victoria" with VIC.

<img width="255" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/e71dced6-7c50-4560-a57b-6dd930d48049">
<img width="257" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/30b19074-cae5-4c73-8faf-e03a17cf62f6">


# Transaction Data quality assessment 
The Transactions table encompasses "transaction_id", "product_id", "customer_id", "transaction_date", "online_order", "order_status", "brand", "product_line", "product_class", "product_size", "list_price", "standard_cost", "product_first_sold_date"

The columns below has inconsistent values, with empty rows. 
I cleaned the empty rows by using replace value option, to replace the empty with "Null".

<img width="633" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/7b82f31e-833a-40ce-91fc-8e3caee9d3ac">

<img width="609" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/e9799e6c-e47a-4d96-8fc5-4375968dc6e1">

# Customer Demopgrapic Data quality assessment
The Customer Demographic table contains columns which includes details such as name, gender, purchases from the past three years, date of birth, job information, wealth segment, deceased status, car ownership, and tenure.

The Customer demographic table cotains some inconsistent values and empty rows. I cleaned the empty rows by using replace value option, to replace the empty with "Null" while the empty rows(null or unknown dates) in the DOB column was replaced with '01/01/1900' as default.

<img width="638" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/cd4f69d7-699f-4916-af81-bad1daf2a25c">

<img width="623" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/afd28e0e-26d3-45a8-8657-c1352185ee37">

<img width="493" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/59febbdd-76d9-49c3-a3d1-8f30c814023d">

The genger column has inconsistent values, the replaced value option was used to replace"F" with "Female" and "M" With "Male".

<img width="254" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/5d2b70e7-c9d4-4694-bac8-cfd9d9f39e2e">



<img width="258" alt="image" src="https://github.com/ucnkwocha/KPMG-Virtual-Data-Analyst-intern-project/assets/155919216/a6fc4a12-1297-4b8b-aaed-d8aa4daf1b53">

The job title with empty values was replaced with "Null"
The tenure with empty values was replaced with 0

