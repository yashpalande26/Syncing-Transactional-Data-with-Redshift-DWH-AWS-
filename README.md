# Syncing-Transactional-Data-with-Redshift-DWH-AWS:

In my project, I orchestrated the seamless synchronization of transactional data stored in an AWS RDS (MySQL) with our Redshift data warehouse. Leveraging AWS components such as Data Pipeline, Lambda, and Glue, I established an efficient data pipeline.

The workflow encompassed:

1. Data Extraction: AWS Data Pipeline periodically extracted transactional data from RDS and transformed it into CSV files.

2. Data Lake Storage: These CSV files were stored in S3 data lakes for easy accessibility.

3. Transformation: AWS Lambda functions triggered AWS Glue jobs, where PySpark scripts were utilized to clean and transform the data.

4. Data Warehousing: The transformed and refined data found its home in our Redshift data warehouse, ready for analysis.

5. Report Generation: Utilizing AWS Quicksight, I created insightful reports, unlocking the full potential of the integrated data.

This project showcases my proficiency in setting up data pipelines, automating ETL processes, and harnessing AWS services to seamlessly sync and analyze data between different systems.
