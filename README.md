# bakbash-Crowdfunding_ETL Project2
## Introduction
ETL (Extract, Transform & Load) is a crucial skill for handling data in the real world. This project focuses on extracting, transforming, and loading data from various sources to create a clean, up-to-date, and accurate dataset. The primary goal is to empower users to manipulate data effectively, fix formatting issues, and gain meaningful insights. The project uses the data mentioned below for extraction, transformation, and loading.
## Sources of Data
### Resources Folder:
•	ccontacts.csv
•	campaign.csv
•	subcategory.csv
•	category.csv
•	contacts.xlsx
•	crowdfunding.xlsx
## Database Type for Final Production Environment
Description: The final production environment will use a Relational (SQL) database for storing and managing the data.
•	Database Type: Relational (SQL)
•	Data Cleaning and Processing: Jupyter Notebook
•	Packages Used: pandas, numpy, datetime
•	Data Loading: pgAdmin
An Entity Relationship Diagram (ERD) will be created to visually represent the database structure.
## ERD

![Screenshot 2024-01-23 at 8 34 20 PM](https://github.com/bakbash/Crowdfunding_ETL/assets/148186521/e43f219d-3dad-4c8a-ade7-dfd8c07e6b24)

## Conclusion
The data suggests that certain categories and subcategories are more successful in crowdfunding. The United States, Canada, and the United Kingdom show the highest crowdfunding support.
Project Outline
Instructions
The instructions for this mini project are divided into the following subsections:
1.	Create the Category and Subcategory DataFrames
•	Extract and transform crowdfunding.xlsx data to create category and subcategory DataFrames.
•	Export DataFrames as category.csv and subcategory.csv.
2.	Create the Campaign DataFrame
•	Extract and transform crowdfunding.xlsx data to create a campaign DataFrame.
•	Export DataFrame as campaign.csv.
3.	Create the Contacts DataFrame
•	Choose Option 1 or Option 2 for extracting and transforming data from contacts.xlsx.
•	Export DataFrame as contacts.csv.
4.	Create the Crowdfunding Database
•	Sketch an ERD using QuickDBD.
•	Create a table schema for each CSV file in crowdfunding_db_schema.sql.
•	Create a new Postgres database named crowdfunding_db.
•	Create tables in the correct order using the database schema.
•	Verify table creation and import CSV files.
