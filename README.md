# ETL-Project
In this project, Spar Nord Bank is trying to observe the withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency. Apart from this, other insights also have to be drawn from the data.

## Broadly the following tasks are performed in this project-

- Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.
- Transforming the transactional data according to the given target schema using PySpark. 
- This transformed data is to be loaded to an S3 bucket.
- Creating the Redshift tables according to the given schema.
- Loading the data from Amazon S3 to Redshift tables.
- Performing the analysis queries.

## Coming to the analysis part, the task is to carry out the calculations to perform the following analytical queries:

- Top 10 ATMs where most transactions are in the ’inactive’ state.
- Number of ATM failures corresponding to the different weather conditions recorded at the time of the transactions.
- Top 10 ATMs with the most number of transactions throughout the year.
- Number of overall ATM transactions going inactive per month for each month.
- Top 10 ATMs with the highest total amount withdrawn throughout the year.
- Number of failed ATM transactions across various card types.
- Top 10 records with the number of transactions ordered by the ATM_number, ATM_manufacturer, location, weekend_flag and then total_transaction_count, on weekdays and on weekends throughout the year.
- Most active day in each ATMs from location "Vejgaard".
