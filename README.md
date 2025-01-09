# Redfin-Analytics-Python-ETL-Pipeline-with-Apache-Airflow
![redfin](https://github.com/user-attachments/assets/8393cb53-593f-4921-8730-bc9b5fd2888f)


Fully Automated ETL Pipeline for Redfin Analytics
This project demonstrates a fully automated ETL (Extract, Transform, Load) pipeline designed for Redfin Analytics. It extracts real estate data, processes and transforms it, and loads it into Snowflake for real-time analysis and visualization.

Pipeline Architecture
Data Extraction:

Extracts real estate data from Redfin’s API using Python.
Stores raw data in Amazon S3 for further processing.
Data Transformation:

Cleans, reshapes, and filters raw data using Python for optimized analytics.
Stores transformed data in a separate S3 bucket.
Orchestration:

Utilizes Apache Airflow on AWS EC2 to schedule and manage the pipeline workflow.
Ensures task execution in the correct order with fault-tolerance.
Data Loading:

Loads transformed data into Snowflake using SnowPipe for real-time ingestion and querying.
Visualization:

Enables real-time analytics and trend visualization through BI tools connected to Snowflake.
Technologies Used
Python: Data extraction and transformation.
Amazon S3: Storage for raw and processed data.
Apache Airflow: Workflow orchestration and automation.
AWS EC2: Hosting for the Airflow instance.
Snowflake: Data warehousing and analytics.
SnowPipe: Automated data loading into Snowflake.
How to Run the Project
Clone this repository.
Install dependencies using requirements.txt.
Configure Apache Airflow on an AWS EC2 instance.
Set up connections to your Amazon S3 buckets and Snowflake account.
Trigger the Airflow DAG to initiate the pipeline.
Acknowledgments
Special thanks to Saylani Mass IT Training Program and Sir Qasim Hassan for their invaluable guidance and mentorship throughout this project.
