# ETL-Data-Pipeline-on-AWS-EMR-Cluster
In this project we will visualize the sales data uploaded in AWS S3 bucket, processed in AWS EMR and visualized in Tableau

# Techstacks used
  - AWS S3
  - AWS EMR - 1 primary & 1 core node (m5.xlarge)
  - Hive
  - Tableau

# Steps Followed 
    1. Create an S3 bucket in AWS
    2. Upload sales data into the S3
    3. Create apprpriate IAM role for EMR ON EC2
    3. Create an EMR cluster on AWS which has required services.
    4. Create Hive external table to point to the data in S3
    5. Perform ETLs on Hive table and store it in final Hive table
    6. Connect Hive final table in AWS EMR to tableau in local and plot the graphs

# Architecture Diagram
![alt text](image.png)