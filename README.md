# Module13_Project2_Crowdfunding_ETL<br>
* --**#This Crowdfunding_ETL mini project is about**-- <br>
    * Building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. 
    * Generate category.csv and subcategory.csv as result of part 1 'Create the Category and Subcategory DataFrames' analysis
    * Generate campaign.csv as result of part 2 'Create the Campaign DataFrame' analysis
    * Generate contacts.csv as result of part 3 'Create the Contacts DataFrame' analysis
    * Using the csv files create an ERD and a table schema
    * Finally upload the four CSV data file data into a Postgres database

* --**TEAM**--<br> Two branches were created for this analysis and the final combined output is merged into main branch. <br>
Each team member contributed the below <br>
 -- Sujatha Alagarsamy - performed etl analysis for part 1 and 4. Branch - etl_mini_project_part1-4<br>
 -- Kent Roth - performed etl analysis for part 2 and 3. Branch - etl_mini_project_part2-3 <br>

*************----------Content under Crowdfunding_ETL repository----------*************<br>
* --Resources Folder contains
    * crowdfunding.xlsx and contacts.csv.xlsx-- input data source file for Crowdfunding_ETL analysis
    * campaign.csv -- output csv file from part 2 Create the Campaign DataFrame analysis
    * category.csv -- output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * subcategory.csv -- output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * contacts.csv -- output csv file from part 3 Create the Contacts DataFrame analysis 
* --ETL_Mini_Project_ASujatha_KRoth.ipynp - Solved jyupter notebook for Part1,2 and 3 analysis
* --crowdfunding_db_StepByStep_Solution.pdf contains each step-by-step process on how part 4 database assignment is done.

*************----------To Execute the Crowdfunding_ETL Jupyter source file(part 1, 2 and 3) ----------*************<br>
* --Open the ETL_Mini_Project_ASujatha_KRoth.ipynp (Jupyter Source File) using Visual studio code
* --Ensure correct Kernel is selected. 
* --Ensure required dataset is under Resources folder and the Resource folder is placed in the same level as the Jupyter source file is placed to avoid error.
* --Click Run All or Run individual code in sequence it is written. Running the code block in between might throw error as the variables used in that code block might be defined in the prior code block. Hence recommended to Run All to ensure it is run in sequence.
* --Ensure four csv out files mentioned below is generated under resources folder
    * campaign.csv -- output csv file from part 2 Create the Campaign DataFrame analysis
    * category.csv -- output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * subcategory.csv -- output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * contacts.csv -- output csv file from part 3 Create the Contacts DataFrame analysis

*************----------To Execute/verify the Crowdfunding_ETL Database analysis (part 4) ----------*************<br>
* --Open pgAdmin - Create crowdfunding_db and import required schema and data. Refer crowdfunding_db_StepByStep_Solution.pdf
* --Open Query tool and ensure connection is set to "crowdfunding_db/postgres@PostgreSQL 15".
* --Open crowdfunding_db_select_Queries.sql and execute each query individually by selecting the query and click run to view the output for each data analysis. Executed output response for each of the tables is also present in sql_output folder.

* --**### In conclusion, the ETL Mini Project has provided us with a comprehensive understanding of the ETL process and its applications. That is ###**--<br>
    * Extract data by using Python and Pandas.
    * Transform and clean data by using Python and Pandas and regular expressions.
    * Parse string data into a Python dictionary.
    * Use list comprehensions to make code more readable.
    * Use wildcards, sets, and escape characters in regular expressions to extract information.
    * Use special characters in regular expressions to extract information.
    * Create and use capture groups in regular expressions to extract information.
    * Create an entity relationship diagram from CSV files.
    * Import CSV files into a postgreSQL database.