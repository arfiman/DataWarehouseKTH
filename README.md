# About
Kopi Tengah Hari (KTH) is a small business that sell homemade coffe. The business process used for transaction is customer would need to Pre-Order the coffe, then the coffe is freshly made. KTH only used spreadsheet to record transaction data, which leads to many problem, such as inconsistency and redundant data, hard to analyze, etc. **This project is aimed to help KTH create a neat system using data warehouse for administration and analysis process**. 

# Steps Taken for the Project
The steps taken in this data warehousing project is:
- Understanding the business process
- Defining Grain
- Defining Dimension Table
- Defining Fact Table
- ETL Planning
- ETL
- Dashboarding

# What you Need
- Tools/Platform: SQL Server & Pentaho
- Language: SQL

# Data Source
The data used for this project is non-disclosure, if you interested for more information contact us. 
Some data used are:
- Transaction data
- Expense data
- Income data
- Production data
- Customer data
- etc.

# Steps for ETL
1. Set up environment for running SQL Server & Pentaho
2. Change the config.properties file to match your database configuration
3. For the first time building the data warehouse, run the full_job.kjb inside the ETL One Time Historical folder using Pentaho
4. When the data is updated, run the full_job.kjb inside the ETL Incremental folder using Pentaho to update the data warehouse


