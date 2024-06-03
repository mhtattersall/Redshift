# Redshift
- This repo contains files for a projects using Amazon Redshift data warehouse
- Magazine reviews and associated metadata files are stored in an AWS S3 bucket
- An Amazon Redshift cluster is created in a VPC with subnets
- A Bucket Policy and an IAM Role are defined
- Data is loaded from S3 to Redshift to form 2 tables
- SQL queries are run to with a join on the tables on the Primary Key 'asin'
