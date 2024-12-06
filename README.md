# sql-challenge
This SQL challenge analyzes a company's employee data from the 1980s and 1990s. Data modeling was first done to organize and display the relationship between tables in the database through an Entity Relationship Diagram (ERD). After, the tables were created and analyzed through PostgreSQL. 

## Files
The files are organized as follows:
- **EmployeeSQL:** folder containing SQL queries
    - **analysis.sql:** queries for analysis on employees
    - **setup.sql:** queries for table creation and relationship
- **data:** folder containing individual csv data for each table
- **Employees_ERD.png:** shows table values and type of relationships between tables in the database

## Steps
For the queries to run successfully, these steps must be completed in the following order:
1) From *setup.sql*, run the 'create tables' section
2) From *data*, find the csv data to be imported to their respective tables
3) From *setup.sql*, run the 'create relationships between tables' section
4) From *analysis.sql*, run queries individually for data analysis