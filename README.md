# Crowdfunding_ETL

This repo is for the project 2 ETL for group 3. 
The ETL project is about reading the excel sheets of crowdfunding and contact
into pandas dataframe, then apply series of data transforamtion, extraction, and reorgnising into desired format for further analysis.
As for the project required for data transformation, our group specifically use the Option 1: use python dictionary methods.
After completion, the Option 2: using regular expressions were deleted from the jupyter notebook.
Additionally, the cleaned data is being created into schema, and it can be imported in relational database (postegre) using SQL.

For inspection the Crowdfunding Database, please use the csv files in Resources folder to mannually import into a relational database
Or using the database built-in import from schema to load.
For SQL table creation and data import of the corresponding csv files:
please follow extactly the order of the crowdfunding_db_schema.sql to ensure the correct and successful data import
1: category, 2:subcategory, 3:contacts, 4:campaigns

## Content:
The repo contains Resources folder for all the original excel files and the extracted csv files for inspection and SQL database import.
The .ipynb notebook contains all source code for the project.
The .txt file for using quickdbd when skeching the visual ERD.
The ERD diagram
The SQL schema file for table creation.

## Group 3 allocations:
Ziyue Zhou (Jacky): group leader
 - repository creation, category, subcategory, campaign dataframes creation and csv file export

Yuqi (Freya) Huang: contributor group member
 - Create the Crowdfunding database, ERD creation, Schema craetion, SQL file creation.

Lim Hung (Hansen): contributor group member
 - Option 1 entire part (contacts dataframe creation and csv file export)
