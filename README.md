# bakbash-Crowdfunding_ETL Project2

## Introduction

ETL (Extract, Transform & Load) is a crucial skill for handling data in the real world. This project focuses on extracting, transforming, and loading data from various sources to create a clean, up-to-date, and accurate dataset. The primary goal is to empower users to manipulate data effectively, fix formatting issues, and gain meaningful insights. The project uses the data mentioned below for extraction, transformation, and loading.

## Sources of Data
### Resources Folder:
- ccontacts.csv
- campaign.csv
- subcategory.csv
- category.csv
- contacts.xlsx
- crowdfunding.xlsx

## Database Type for Final Production Environment

- Database Type: Relational (SQL)
- Data Cleaning and Processing: Jupyter Notebook
- Packages Used: pandas, numpy, datetime
- Data Loading: pgAdmin
An Entity Relationship Diagram (ERD) will be created to visually represent the database structure.
## ERD

![Screenshot 2024-01-23 at 8 34 20 PM](https://github.com/bakbash/Crowdfunding_ETL/assets/148186521/e43f219d-3dad-4c8a-ade7-dfd8c07e6b24)

## Project Outline
1.	Create the Category and Subcategory DataFrames
- Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame 
- Export the category DataFrame as category.csv and save it to your GitHub repository.
- Extract and transform the crowdfunding.xlsx Excel data to create a subcategory
- Export the subcategory DataFrame as subcategory.csv and save it to your GitHub repository.
2.	Create the Campaign DataFrame
- Extract and transform crowdfunding.xlsx data to create a campaign DataFrame.
- Export DataFrame as campaign.csv.
3.	Create the Contacts DataFrame
- Choose Option 1 or Option 2 for extracting and transforming data from contacts.xlsx.
- Export DataFrame as contacts.csv.
4.	Create the Crowdfunding Database
- Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBD
- Create a table schema for each CSV file in crowdfunding_db_schema.sql.
- Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to your GitHub repository.
- Create a new Postgres database, named crowdfunding_db.
- Using the database schema, create the tables in the correct order to handle the foreign keys.
- Verify the table creation by running a SELECT statement for each table.
- Import each CSV file into its corresponding SQL table.
- Verify that each table has the correct data by running a SELECT statement for each.
