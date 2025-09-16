# Data Warehouse Configuration

This repository contains the infrastructure configuration and environment settings for the data warehouse pipeline.

## warehouse_config.cfg file in warehouse folder contains  

```
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[CLUSTER]  
HOST='<Redshift Cluster Endpoint>'  
DB_NAME='<db-name>'  
DB_USER='<db-user-name>'  
DB_PASSWORD='<db-password>'  
DB_PORT=<db-port, default 5439>  
  
[IAM_ROLE]  
ARN=<Redshift ARN role>
  
  
[STAGING]  
SCHEMA=<Warehouse-staging-schema>  
  
[WAREHOUSE]  
SCHEMA=<Warehouse-schema>  
  
  
[BUCKET]  
LANDING_ZONE=<landing-zone-bucket>  
WORKING_ZONE=<working-zone-bucket>
PROCESSED_ZONE=<processed-zone-bucket>
```

## Maintainer

Umapathi Varma
Senior Data Engineer
Email: umapathivarma.26@gmail.com
LinkedIn: www.linkedin.com/in/umapathiv

About the Developer:
Umapathi is a Data Engineer with 6+ years of experience designing ETL pipelines, lakehouse platforms, warehouses, and analytics solutions across AWS, Azure, and GCP. He specializes in Python, SQL, Spark, and cloud storage, delivering reliable batch and streaming orchestration for production workloads at scale.