# Crowdfunding-ETL
Creating **Data Pipeline** for "Independent Funding"  crowdfunding platform using ETL process (extract, transform, and load).

![This is an image](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/ETL.png)

## Project Summary phases:

* Create an ETL pipeline that moves raw data to a SQL database.
* Extract data from an external file by using Python and Pandas.
* Use regular expressions to extract numbers and text.
* Clean and transform data by using Python and Pandas.
* Design a database and a table schema by using an entity relationship diagram (ERD).
* Load data into a PostgreSQL database.
* Perform data analysis by using SQL queries.

Initial steps in the project included extracting and transforming the raw data from the large Excel file, followed by "clean and transform" steps in the code ( [Crowdfunding-ETL](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/Crowdfunding_ETL.ipynb) [Extract-Transform_final_code](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/Extract-Transform_final_code.ipynb.ipynb) ).

After exporting  the DataFrames to CSV files, a table schema was created using an entity relationship diagram (ERD)

![This is an image](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/crowdfunding_db_relationships.png)

After loading the data from cvs files into crowdfunding Data Base [SQL queries](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/crowdfunding_SQL_Analysis.sql) were executed to generate reports for stakeholders.

As an example, one of reguest was to send an email to each backer to let them know how much of the goal remains for each live campaign that they’ve pledged.
[SQL Querie result : ](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/crowdfunding_SQL_Analysis.sql) 

![This is an image](https://github.com/MilosPopov007/Crowdfunding-ETL/blob/main/Goal_left_contacts.png)
