# ETL-Project
In this project, Spar Nord Bank is trying to observe the withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency. Apart from this, other insights also have to be drawn from the data.

## Broadly the following tasks are performed in this project-

- Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.
- Transforming the transactional data according to the given target schema using PySpark. 
-- This transformed data is to be loaded to an S3 bucket.
-- Creating the Redshift tables according to the given schema.
-- Loading the data from Amazon S3 to Redshift tables.
-- Performing the analysis queries.
