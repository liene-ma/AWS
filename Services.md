# Amazon Web Service Cloud Platform

### AWS Management Console
simple and intuitive user interface + mobile app

### AWS Command Line Interface
CL tool to manage AWS services, automate through scripts

### Software Development Kits 
Application program interface (API) simplifies using AWS services to suit your prog lang or platform

### Analytics

**Amazon Athena**
serverless, interactive DB with SQL capabilities, query data in S3, pay per query, output results back to S3, secured through IAM

**EMR** 
Elastic MapReduce, helps to create Hadoop clusters (Big Data) to analyze and process vast amounts of data. Clusters can 
be made of hundreds of EC2 instances, EMR takes care of all the provisioning and configuration. Use of Apache Spark, HBase,
Presto, Flink and interact with S3 and Amazon DynamoDB.

**Amazon CloudSearch**
service to simply and cost-effectively set up, manage and scale search solution for websites, applications. Supports 34 
languages, highlighting, autocomplete, geospatial search.

**Amazon Elasticsearch Service**
asy to deploy, secure, operate, and scale Elasticsearch to search, analyze, and visualize data in real-time. With Amazon 
Elasticsearch Service, you get easy-to-use APIs and real-time analytics capabilities to power use-cases such as log 
analytics, full-text search, application monitoring, and clickstream analytics, with enterprise-grade availability, 
scalability, and security.

**Amazon Kinesis**
easy to collect, process and analyze real-time, streaming data at any scale. ingest real-time data such
as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, 
and other applications 

**Kinesis Data Streams** low latency streaming to ingest data at scale from
hundreds of thousands of sources \
**Kinesis Data Firehose** load streams into S3, Redshift, ElasticSearch, etc... \
**Kinesis Data Analytics** perform real-time analytics on streams using SQL \ 
**Kinesis Video Streams** monitor real-time video streams for analytics or ML

**Amazon Redshift** 
fast, scalable data warehouse. Based on PostgreSQL, it's OLAP - online analytical processing, load data once every hour, not every second.
10x better performance than other data warehouses, columnar storage of data, pay as you go based on the instances provisioned,
SQL interface for performing queries, integrate tools such as Quicksight, Tableau.

**Amazon Quicksight** 
fast, cloud-powered, serverless business intelligence service; create, publish interactive dashboards, embed dashboards into applications.
Automatically scalable, embeddable with per-session pricing. 

**AWS Data Pipeline**
web service to process and move data between different AWS compute and storage services.You can regularly access your 
data where it’s stored, transform and process it at scale and transfer results to AWS services like S3, RDS, DynamoDB, EMR.

**AWS Glue**
managed extract, transform and load (ETL) service to prepare and transform data for analytics. Fully serverless. Can be used
by Athena, Redshift, EMR.

**AWS Lake Formation**
service to easily set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that 
stores all your data, both in its original form and prepared for analysis. A data lake enables you to break down data silos 
and combine different types of analytics to gain insights and guide better business decisions.

**Amazon MSK**
Amazon Managed Streaming for Apache Kafka - service to build and run applications that use Apache Kafka to process streaming data.
Apache Kafka is an open-source platform for building real-time streaming data pipelines and applications.

