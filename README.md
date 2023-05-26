# Module13_Project2_Crowdfunding_ETL<br>
*************----------Content under Crowdfunding_ETL repository----------*************<br>
* --Resources Folder contains
    * crowdfunding.xlsx and contacts.csv.xlsx-- input data source file for Crowdfunding_ETL analysis
    * campaign.csv -- output csv file from part 2 Create the Campaign DataFrame analysis
    * category.csv --  output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * subcategory.csv --  output csv file from part 1 Create the Category and Subcategory DataFrames analysis 
    * contacts.csv -- output csv file from part 3 Create the Contacts DataFrame analysis 
* --ETL_Mini_Project_ASujatha_KRoth.ipynp - Solved jyupter notebook for Part1,2 and 3 analysis
* --crowdfunding_db_StepByStep_Solution.pdf contains each step-by-step process on how part 4 database assignment is done.

*************----------To Execute the Crowdfunding_ETL Jupyter source file ----------*************<br>

* --Open the ETL_Mini_Project_ASujatha_KRoth.ipynp (Jupyter Source File) using Visual studio code
* --Ensure correct Kernell is selected. 
* --Ensure required dataset is under Resources folder and the Resource folder is placed in the same level as the Jupyter source file is placed to avoid error.
* --Click Run All or Run individual code in sequence it is written. Running the code block in between might throw error as the variables used in that code block might be defined in the prior code block. Hence recommended to Run All to ensure it is run in sequence.

*************----------To Execute/verify the Crowdfunding_ETL analysis ----------*************<br>
* --Open pgAdmin - Create EmployeeDB and import required schema and data. Refer crowdfunding_db_StepByStep_Solution.pdf
* --Open Query tool and ensure connection is set to "crowdfunding_db/postgres@PostgreSQL 15".
* --Open crowdfunding_db_select_Queries.sql and execute each query individually by selecting the query and click run to view the output for each data analysis.  Executed output response for each of the table is also present in sql_output folder
