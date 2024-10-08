# Establishing the Link Between Power BI and SQL Database
### Project Overview 
----
This repository shows a step-by-step guide for connecting SQL database and Power BI. The goal here is to input the top 25 information from the data. To achieve this, I utilized SQL - Structured Query Language and Power - BI      
### Making the Connection Between SQL Database and Power BI 
----
- Load the data into SQL by right clicking on the desired database the clicking on TASK and then IMPORT FLAT FILE. 
-To get data from SQL Server into Power BI click on the get data button and select SQL Server database from the dropdown menu.
- Fill out the connection details by entering the Server name and Database name. For Data connectivity mode, select Import. Click advanced Options and input the SQL query in the advanced options, write your SQL query to return only the necessary data for analysis and click OK.
``` SQL
Select Top 25 * from Bank_Term_Deposit_Subscription;
```
- Then the preview loads, verify the information and click load
### Conclusion
- Ensure all necessary prerequisites are met before starting the connection process.
- It is very important to verify data accuracy at each step of the integration process because failaure to do so will affect the overall analysis 
  
