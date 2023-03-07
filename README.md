# Data Engineering Intensive Training Program

**Hit the ⭐️ button if you like the repo.**

## Join the Program

Join the 55-hour intensive training program now.

Price is $175 /- 

[*USE DEITP30 coupon fo 30% discount.* *OFFER VALID FOR LIMITED TIME ONLY]*

[Book your seat today!](https://sparshcloud.typeform.com/to/fX9s14Ir)

## Curriculum

### Developer Foundations

* [ ] Visual Studio Code (vscode) [[link to note](01-foundations/developer/vscode/)]
  * [ ] Download and Install vscode
  * [ ] Understand vscode features
  * [ ] Install extensions in vscode
* [ ] Anaconda [[link to note](01-foundations/developer/anaconda/)]
  * [ ] Download and Install Anaconda
  * [ ] Create virtual environment in anaconda
  * [ ] Create jupyter notebook in vscode and connect to venv
* [ ] Github [[link to note](01-foundations/developer/github/)]
  * [ ] Create github account
  * [ ] Install git cli
  * [ ] Create git repo and add students as collaborator
  * [ ] Connect local workspace to git repo
  * [ ] Learn git commands
* [ ] Bash [[link to note](01-foundations/developer/bash/)]
  * [ ] Starting bash terminal in vscode
  * [ ] Learn bash commands
* [ ] DBeaver [[link to note](01-foundations/developer/dbeaver/)]
  * [ ] Download and Install DBeaver

### Data Engineering Foundations

* [ ] Data Engineering Must-to-know concepts [[link to note](01-foundations/data-engineering/)]
  * [ ] What is Data Engineering?
  * [ ] Role of Data Engineering in Organizations
  * [ ] Skills required to become a Data Engineer
  * [ ] Data engineer versus data scientist
  * [ ] What is data lake and data warehouse?
  * [ ] What is medallion architecture?
  * [ ] What is EL, ETL and ELT?
* [ ] Data Engineering most common interview questions [[link to note](01-foundations/data-engineering/)]
* [ ] Case study: Fair - Data Ingestion with a Cloud Data Platform [[link to note](a3-casestudies/fair.md/)]
* [ ] Case study: Harmony - Responsive Data Pipeline [[link to note](a3-casestudies/harmony.md/)]
* [ ] Case study: Panoramic - Simplifying Data Ingestion, Transformation, And Delivery [[link to note](a3-casestudies/panoramic.md/)]

### Cloud Essentials

* [ ] Cloud Basics
  * [ ] What is Cloud Computing
  * [ ] Types of Cloud
  * [ ] Benefits of Cloud
  * [ ] Types of Cloud Services
* [ ] Create Cloud Account
  * [ ] Create AWS Account
  * [ ] Create GCP Account
  * [ ] Create Azure Account
* [ ] AWS Services Walkthrough
  * [ ] Storage Services - [S3](01-foundations/cloud/aws/s3.md), [RDS](01-foundations/cloud/aws/rds.md), Redshift, Keyspace
  * [ ] ETL Services - [Glue](01-foundations/cloud/aws/glue.md)
  * [ ] Compute Services - Lambda, EMR, [EC2](01-foundations/cloud/aws/ec2/), Athena
  * [ ] DevOps Services - Cloudformation, [IAM](01-foundations/cloud/aws/iam/), Secrets Manager
* [ ] GCP Services Walkthrough
  * [ ] Storage Services - GCS, Cloud SQL, BigQuery, BigTable
  * [ ] Compute Services - Cloud Functions, Dataproc, Cloud Compute, Dataflow
  * [ ] DevOps Services - IAM
* [ ] Azure Services Walkthrough
  * [ ] Storage Services - Blob Storge, DataLake Gen2 buckets, Azure SQL Databases
  * [ ] Compute Services - Databricks/Synapse Analytics, Azure Data Factory
  * [ ] DevOps Services - IAM
* [ ] AWS Account Setup [[source code](01-foundations/cloud/aws/lab-aws-setup/)]
  * [ ] Install AWS CLI
  * [ ] Create IAM user and generate credentials
  * [ ] Setup AWS credentials
* [ ] AWS IAM Service [[source code](01-foundations/cloud/aws/iam/)]
  * [ ] Create policies and roles
  * [ ] Attach policies to the roles
* [ ] AWS S3 Service
  * [ ] Learn AWS CLI S3 essential commands
  * [ ] Copy and Sync data to/from S3 with AWS CLI
* [ ] AWS RDS Service
  * [ ] Create database in RDS DBMS and generate credentials
  * [ ] Connect to RDS DBMS in DBeaver
* [ ] AWS Secrets Manager Service [[source code](01-foundations/cloud/aws/secrets-manager/)]
  * [ ] Create a Secret in Secrets Manager Vault
  * [ ] Get the credential using AWS CLI
* [ ] Create VPC [[link to note](01-foundations/cloud/aws/vpc/lab-create-your-first-vpc/)]
* [ ] Containers Services - ECS and EKS [[link to note](01-foundations/cloud/aws/containers-on-aws.md/)]
* [ ] Data Migration Service (DMS) [[link to note](01-foundations/cloud/aws/dms.md/)]

### Programming

#### SQL

* [ ] Ingest data from CSV file into MySQL database table [[source code](02-storage/databases/mysql/lab-data-ingestion-to-mysql/)]
* [ ] SQL Basics to Advanced Primer [[source code](01-foundations/language/sql/mode/)]
  * [ ] SQL Basics - Select, Limit, Where, Comparison and Logical operators, Order by
  * [ ] SQL Intermediate - Aggregations, Group by, Case statements, Joins
  * [ ] SQL Advanced - Dates, Text, Subqueries, Window functions, Optimizations
* [ ] Postgres SQL basics to advanced [[source code](01-foundations/language/sql/lab-postgres-queries/)]
* [ ] Running Dates, String and Advanced queries in Postgres on Sales data [[source code](02-storage/databases/postgres/lab-postgres-sales/)]
* [ ] Working with Book dataset on SQLite database [[source code](02-storage/databases/sqlite/lab-sqlite-basics/)]
* [ ] Challenge - Yammer Advanced Analytics [[source code](01-foundations/language/sql/challenges/yammer/)]
* [ ] Challenge - BrainTree SQL Code Challenge [[source code](01-foundations/language/sql/challenges/braintree/)]

#### Python

* [ ] Lists and dictionaries
* [ ] For loops and while loops
* [ ] Functions and Inline functions
* [ ] Read/Write and Manipulate Data using Pandas
* [ ] Pulling data from APIs using requests library
* [ ] Reading data from flat files - csv, json, parquet, avro, excel, txt [[source code](02-storage/flat-files/lab-data-loading-python/)]
* [ ] Reading and writing data to databases using psycopg2 and sqlalchemy library
* [ ] Reading data from S3 and athena using aws data wrangler library
* [ ] Pull credentials from Secrets Manager using boto3 library
* [ ] Lab - Exchange Rate ETL process [[source code](01-foundations/language/python/lab-exchange-rate-etl/)]
* [ ] ETL process and reading/writing CSV, JSON and XML files in pandas [[source code](01-foundations/language/python/lab-etl-csv-json-xml/)]
* [ ] Basic Text Handling with Python [[source code](18-nlp/lab-basic-text-handlng-python/)]

#### PySpark

* [ ] Create databricks account
* [ ] Create your first databricks cluster
* [ ] Create your first databricks notebook
* [ ] M&M color balls analysis with PySpark
* [ ] Movielens and Song analysis with PySpark
* [ ] San Francisco Fire Department call analysis with PySpark
* [ ] Connect AWS to PySpark and build an ETL pipeline [[source code](03-processing/databricks/lab-databricks-pyspark-s3/)]

#### Scala

* [ ] Introduction to Scala programming
* [ ] Getting started with Spark Scala
* [ ] Building extract and load pipeline with Scala, S3 and Postgres [[source code](03-processing/databricks/lab-databricks-scala-postgres-s3/)]

### Data Storage

#### Flat Files

* [ ] Introduction to various file formats - CSV, Parquet, JSON, Avro, and ORC [[link to note](02-storage/flat-files/)]
* [ ] Processing JSON data in Python [[source code](02-storage/flat-files/lab-processing-json-data/)]

#### Relational Databases

* [ ] Configuring and Securing Azure SQL Database [[source code](02-storage/databases/azure-sql/lab-securing-azure-sql-databases/)]
  * [ ] This lab covers configuring a Serverless SQL database, Hyperscale SQL database, and securing Azure SQL Database using virtual networks and private links
  * [ ] Recipe 1 - Provisioning and connecting to an Azure SQL database using PowerShell
  * [ ] Recipe 2 - Implementing an Azure SQL Database elastic pool using PowerShell
* [ ] Load CSV data from on-premise to GCP CloudSQL [[source code](02-storage/databases/cloudsql/lab-gcp-cloudsql-nyctaxi/)]
* [ ] db2 BookShop and PetSale Data Ingestion and Stored Procedure [[source code](02-storage/databases/db2/lab-dbt-bookshop-petsale-data-ingestion/)]
* [ ] OLAP Analytics on bank, TPCH and NYC Taxi datasets using DuckDB [[source code](02-storage/databases/duckdb/lab-analytics-bank-tpch-nyctaxi/)]
* [ ] Getting started with Postgres and Python [[source code](02-storage/databases/postgres/lab-postgres-getting-started/)]
* [ ] Use bash shell commands to extract, transform and load data into Postgres [[source code](02-storage/databases/postgres/lab-bash-etl/)]
* [ ] Extract and load food data into Postgres using Python [[source code](02-storage/databases/postgres/lab-extract-and-load-food-data/)]
* [ ] Build a database for crime reports in Postgres [[source code](02-storage/databases/postgres/lab-postgres-crime-reports/)]

#### NoSQL Databases

* [ ] Streaming Data Processing - Streaming Data Pipelines into GCP Bigtable [[source code](02-storage/nosql-databases/bigtable/lab-gcp-streaming-bigtable/)]
* [ ] Fundamentals of Apache Cassandra  [[link to note](02-storage/nosql-databases/cassandra/)]
* [ ] Setup Cassandra in local system [[source code](02-storage/nosql-databases/cassandra/lab-getting-started-with-cassandra/)]
* [ ] Getting started with Cassandra [[source code](02-storage/nosql-databases/cassandra/lab-getting-started-with-cassandra/)]
* [ ] Cassandra on Cloud with Amazon Keyspaces [[source code](02-storage/nosql-databases/cassandra/lab-amazon-keyspaces/)]
* [ ] Fundamentals of DynamoDB [[link to note](02-storage/nosql-databases/dynamodb/)]
* [ ] Getting started with MongoDB [[source code](02-storage/nosql-databases/mongodb/lab-mongodb-basics/)]

#### Data Warehouses

* [ ] Amazon Athena Basics [[link to note](02-storage/warehouses/athena/)]
* [ ] Building Federated Query System using Amazon Athena [[source code](02-storage/warehouses/athena/project-athena-federated/)]
* [ ] GCP BigQuery Basics [[link to note](02-storage/warehouses/bigquery/)]
* [ ] Using BigQuery to do analysis [[source code](02-storage/warehouses/bigquery/lab-bigquery-analysis/)]
* [ ] Bigquery basics command line operations [[source code](02-storage/warehouses/bigquery/lab-bigquery-commandline/)]
* [ ] Creating a Data Warehouse Through Joins and Unions [[source code](02-storage/warehouses/bigquery/lab-bigquery-data-warehousing/)]
* [ ] Build and Optimize Data Warehouses with BigQuery [[source code](02-storage/warehouses/bigquery/lab-bigquery-optimization/)]
* [ ] Optimizing your BigQuery Queries for Performance [[source code](02-storage/warehouses/bigquery/lab-bigquery-query-optimization/)]
* [ ] Building a BigQuery Data Warehouse [[source code](02-storage/warehouses/bigquery/lab-biqeury-building-warehouse/)]
* [ ] Predict Visitor Purchases with a Classification Model in BigQuery ML [[source code](02-storage/warehouses/bigquery/lab-gcp-bigquery-ml/)]
* [ ] NYC Cab Prediction Model in BigQuery ML [[source code](02-storage/warehouses/bigquery/lab-gcp-bigquery-nyctaxi/)]
* [ ] Copy data from S3 into Amazon Redshift [[source code](02-storage/warehouses/redshift/lab-copy-from-s3/)]
* [ ] Create, Train and Deploy Multi Layer Perceptron (MLP) models using Amazon Redshift ML [[source code](02-storage/warehouses/redshift/lab-redshift-ml/)]
* [ ] Connect and Query Redshift with Python [[source code](02-storage/warehouses/redshift/lab-redshift-python/)]
* [ ] Implement a slowly changing dimension in Amazon Redshift [[source code](02-storage/warehouses/redshift/lab-redshift-scd/)]
* [ ] Load NYC Taxi csv data into Redshift using Python AWS Data Wrangler [[source code](02-storage/warehouses/redshift/lab-redshift-taxi/)]
* [ ] Advanced Data Analytics on TPCH Sales data in Redshift [[source code](02-storage/warehouses/redshift/project-redshift-sales/)]
* [ ] Difference between databases, warehouses, lakes and lakehouses
* [ ] OLTP vs OLAP technologies
* [ ] Loading data into Redshift warehouse with S3 staging and COPY command

#### Data Lakes and Lakehouses

* [ ] Working with S3 using Boto3 in Python [[source code](02-storage/datalakes/lab-s3-boto3/)]
* [ ] Creating and Managing Data in Azure Data Lake [[source code](02-storage/datalakes/lab-adl-create-manage-data/)]
* [ ] Securing and Monitoring Data in Azure Data Lake [[source code](02-storage/datalakes/lab-adl-securing-monitoring-lakes/)]
* [ ] Introduction to Data Lakehouses - Delta, Iceberg and Hudi [[link to note](02-storage/lakehouses/)]
* [ ] Building a data lake for a healthcare company with AWS, S3 and Athena [[source code](02-storage/datalakes/lab-datalake-healthcare-s3-glue-athena/)]
* [ ] Working with AWS S3 and Delta lake in Databricks

### Data Processing

#### Batch Data Processing

* [ ] Creating and Monitoring Production Data Processing Jobs in Databricks
* [ ] Creating and submitting Word count Spark Job in EMR Serverless
* [ ] Building a near real-time serverless data pipeline with AWS lambda function [[source code](03-processing/aws-lambda-function/lab-lambda-csv-parquet/)]
* [ ] Building an ELT pipeline for a cab service company using dbt and Postgres
* [ ] Data Transformation with PySpark using Amazon EMR Serverless Application [[source code](03-processing/aws-emr/lab-emr-serverless/)]
* [ ] Advanced Data Engineering and Data Processing with AWS Glue Jobs [[source code](03-processing/aws-glue/lab-glue-advanced/)]
* [ ] Handle UPSERT data operations using open-source Delta Lake and AWS Glue [[source code](03-processing/aws-glue/lab-glue-deltalake-cdc-upsert/)]
* [ ] Create your own reusable visual transforms for AWS Glue Studio [[source code](03-processing/aws-glue/lab-glue-studio-custom-transforms/)]
* [ ] Tickets ETL with Glue Studio [[source code](03-processing/aws-glue/lab-glue-studio-tickets/)]
* [ ] CSV to Parquet Transformation with Glue Studio [[source code](03-processing/aws-glue/lab-csv-to-parquet-conversion/)]
* [ ] Processing Data Using Azure Databricks - Configuring the Azure Databricks environment, Integrate Databricks with Azure Key Vault, Mounting an Azure Data Lake container in Databricks, Processing data using notebooks, Scheduling notebooks using job clusters, Working with Delta Lake tables [[source code](03-processing/azure-databricks/lab-data-processing-azure-dbr/)]
* [ ] Build Data Pipeline with HDInsight [[source code](03-processing/azure-hdinsight/lab-simple-data-processing/)]
* [ ] Processing Data Using Azure Synapse Analytics [[Source code](03-procesing/azure-synapse-analytics/lab-data-processing-synapse-analytics/)]
  * [ ] This lab covers exploring data using Synapse Serverless SQL pool, processing data using Synapse Spark Pools, Working with Synapse Lake database, and integrating Synapse Analytics with Power BI
  * [ ] Recipe 1 - Provisioning an Azure Synapse Analytics workspace
  * [ ] Recipe 2 - Analyzing data using serverless SQL pool
  * [ ] Recipe 3 - Provisioning and configuring Spark pools
  * [ ] Recipe 4 - Processing data using Spark pools and a lake database
  * [ ] Recipe 5 - Querying the data in a lake database from serverless SQL pool
  * [ ] Recipe 6 - Scheduling notebooks to process data incrementally
* [ ] Transforming Data Using Azure Synapse Dataflows [[Source code](03-procesing/azure-synapse-analytics/lab-azure-synapse-dataflows/)]
  * [ ] This lab focuses on performing transformations using Synapse Dataflows, optimizing data flows using partitioning, and managing dynamic source schema changes using schema drifting
  * [ ] Recipe 1 - Copying data using a Synapse data flow
  * [ ] Recipe 2 - Performing data transformation using activities such as join, sort, and filter
  * [ ] Recipe 3 - Monitoring data flows and pipelines
  * [ ] Recipe 4 - Configuring partitions to optimize data flows
  * [ ] Recipe 5 - Parameterizing mapping data flows
  * [ ] Recipe 6 - Handling schema changes dynamically in data flows using schema drift
* [ ] Implementing the Serving Layer Star Schema [[Source code](03-procesing/azure-synapse-analytics/lab-implementing-star-schema/)]
  * [ ] In this lab, we will learn about implementing the serving layer, which involves implementing star schemas, techniques to read and write different data formats, sharing data between services such as SQL and Spark, and more
  * [ ] Once you complete this lab, you should be able to understand the differences between a Synapse dedicated SQL pool versus traditional SQL systems for implementing the Star schema, the various ways of accessing Parquet data using technologies such as Spark and SQL, and the details involved in storing metadata across services
  * [ ] All this knowledge should help you build a practical and maintainable serving layer in a data lake
  * [ ] Recipe 1 - Delivering data in a relational star schema
  * [ ] Recipe 2 - Implementing a dimensional hierarchy
  * [ ] Recipe 3 - Delivering data in Parquet files
  * [ ] Recipe 4 - Maintaining metadata
* [ ] Getting started with Apache Beam [[source code](03-processing/beam/lab-getting-started-with-beam/)]
* [ ] MapReduce in Beam using Python [[source code](03-processing/beam/lab-gcp-beam-mapreduce/)]
* [ ] Building a Cybersecurity Lakehouse for CrowdStrike Falcon Events in Databricks [[source code](03-processing/databricks/lab-cybersecurity-databricks/)]
* [ ] Databricks AWS Integration and Clickstream Analysis [[source code](03-processing/databricks/lab-databricks-clickstream/)]
* [ ] Create an elementary Data Lakehouse using Databricks and the Delta lake technology [[source code](03-processing/databricks/lab-databricks-deltalake/)]
* [ ] Delta Lake Optimizations [[source code](03-processing/databricks/lab-deltalake-optimizations/)]
* [ ] Compare dbt and Delta Live Tables (dlt) for data transformation [[source code](03-processing/databricks/lab-dlt-dbt/)]
* [ ] Unlocking the Power of Health Data With a Modern Data Lakehouse [[source code](03-processing/databricks/lab-healthcare-databricks/)]
* [ ] Real-time Health Tracking and Monitoring System [[source code](03-processing/databricks/lab-iot-health-tracker/)]
* [ ] Simplifying Data Engineering and Analytics with Delta [[source code](03-processing/databricks/lab-loan-application/)]
* [ ] Real-Time Point-of-Sale Analytics With the Data Lakehouse [[source code](03-processing/databricks/lab-retail-pos-databricks/)]
* [ ] Data Engineering with Databricks [[source code](03-processing/databricks/project-databricks-de/)]
* [ ] Data Engineer Learner Path with Databricks [[source code](03-processing/databricks/project-learnerbricks/)]
* [ ] Advanced Data Engineering with Databricks [[source code](03-processing/databricks/project-advancedbricks/)]
* [ ] Databricks PySpark Ecommerce Data Processing Case Study [[source code](03-processing/databricks/project-bedbricks/)]
* [ ] Data Pipeline with Databricks PySpark and Superset [[source code](03-processing/databricks/project-databricks-superset/)]
  * [ ] You’ll build a modern, cloud-based, three-layer data Lakehouse
  * [ ] First, you’ll set up your workspace on the Databricks platform, leveraging important Databricks features, before pushing the data into the first two layers of the data lake
  * [ ] Next, using Apache Spark, you’ll build the third layer, used to serve insights to different end-users
  * [ ] Then, you’ll use Delta Lake to turn your existing data lake into a Lakehouse
  * [ ] Finally, you’ll deliver an infrastructure that allows your end-users to perform specific queries, using Apache Superset, and build dashboards on top of the existing data
* [ ] dbt Postgres on Jaffle Shop data [[source code](03-processing/dbt/lab-jaffle-shop/)]
* [ ] dbt Snowflake on Knoema data [[source code](03-processing/dbt/lab-knoema/)]
* [ ] dbt Postgres on NYC Taxi data [[source code](03-processing/dbt/lab-nyctaxi/)]
* [ ] dbt Postgres on Olist Retail data [[source code](03-processing/dbt/lab-olist/)]
* [ ] dbt BigQuery on Stack Exchange data [[source code](03-processing/dbt/lab-stackexchnge/)]
* [ ] Building an ELT Pipeline with dbt and Amazon Redshift on TICKIT data [[source code](03-processing/dbt/lab-tickit/)]
* [ ] dbt Snowflake on TPCH data [[source code](03-processing/dbt/lab-tpch/)]
* [ ] Creating a Data Transformation Pipeline with Cloud Dataprep [[source code](03-processing/gcp-dataprep/lab-gcp-dataprep/)]
* [ ] Running Apache Spark jobs on Cloud Dataproc [[source code](03-processing/gcp-dataproc/lab-gcp-dataproc/)]
* [ ] Churn Analytics Demo with dbt Snowpark Python models [[source code](03-processing/snowpark/churnpark/)]
* [ ] Getting started with dbt and Snowpark [[source code](03-processing/snowpark/dbtsnowpy/)]
* [ ] FIFA prediction model with dbt and Snowpark [[source code](03-processing/snowpark/fifapark/)]
* [ ] Jaffle shop analytics modeling with dbt and Snowpark [[source code](03-processing/snowpark/jafflepark/)]
* [ ] Knoema Regression with dbt Snowpark and Streamlit [[source code](03-processing/snowpark/knoema-regression/)]

#### Stream and Unified Data Processing

* [ ] Apache Druid Fundamentals [[link to note](03-processing/druid/)]
* [ ] Real-time Taxi Price Model based Prediction using Flink [[source code](03-processing/flink/lab-taxi-pricing/)]
* [ ] Real-time Twitter Stream Wordcount using Flink [[source code](03-processing/flink/lab-twitter-stream-processing/)]
* [ ] Build a simple Dataflow Pipeline (Python) [[source code](03-processing/dataflow/lab-gcp-dataflow-pipeline.md/)]
* [ ] Batch Analytics Pipelines with Cloud Dataflow (Python) [[source code](03-processing/dataflow/lab-gcp-dataflow-batch-pipeline.md/)]
* [ ] Providing Side Inputs in Dataflow (Python) [[source code](03-processing/dataflow/lab-gcp-dataflow-side-inputs.md/)]
* [ ] Using Dataflow for Streaming Analytics (Python) [[source code](03-processing/dataflow/lab-gcp-dataflow-stream-pipeline.md/)]
* [ ] Writing an ETL Pipeline using Apache Beam and Cloud Dataflow (Python) [[source code](03-processing/dataflow/lab-gcp-serverless-dataflow.md/)]
* [ ] ETL Processing on Google Cloud Using Dataflow and BigQuery [[source code](03-processing/dataflow/lab-dataflow-bigquery-etl.md/)]
* [ ] Getting started with Kafka and CLI [[source code](03-processing/kafka/lab-kafka-cli/)]
* [ ] Getting started with Kafka and Python [[source code](03-processing/kafka/lab-kafka-python/)]
* [ ] Getting started with Confluent Kafka and Python [[source code](03-processing/kafka/lab-confluent-python/)]
* [ ] Real-time CDC-enabled Extract and Load Pipeline with Kafka on Cloud [[source code](03-processing/kafka/lab-confluent-kafka-faker/)]
* [ ] Real-time fraud detection by applying filter in Kafka topic [[source code](03-processing/kafka/lab-kafka-fraud-detection/)]
* [ ] Kafka Streams for NYC Taxi data [[source code](03-processing/kafka/lab-kafka-nyctaxi/)]
* [ ] Kafka on Cloud with Amazon ECS and Container Orchestration [[source code](03-processing/kafka/lab-kafka-python-ecs/)]
* [ ] Realtime Streaming analytics with Apache Kafka and Spark Streaming [[source code](03-processing/kafka/lab-kafka-spark-streaming/)]
* [ ] Stock Market Kafka Real Time [[source code](03-processing/kafka/lab-kafka-stock-market/)]
* [ ] Data Streaming Pipeline with Kafka for livetolldata [[source code](03-processing/kafka/lab-kafka-toll-analysis/)]
* [ ] Building an event-driven IKEA app with Kafka [[source code](03-processing/kafka/project-ikea/)]
* [ ] Real Time Apache Log Analytics with Kinesis [[source code](03-processing/kinesis/lab-kinesis-apache-logs/)]
* [ ] Real-Time Clickstream Anomaly Detection with Kinesis [[source code](03-processing/kinesis/lab-kinesis-clickstream-anomaly/)]
* [ ] Streaming Data Pipelines with GCP PubSub [[source code](03-processing/pubsub/lab-gcp-pubsub-processing.md/)]
* [ ] Publish Streaming Data into PubSub [[source code](03-processing/pubsub/lab-gcp-pubsub.md/)]
* [ ] Log Analytics and Processing in Real-Time (Apache Flink, Beam, Amazon Kinesis Data Analytics) [[source code](12-capstones/kinesis-flink-beam/)]
* [ ] Streaming ETL pipeline with Apache Flink and Amazon Kinesis Data Analytics [[source code](12-capstones/kinesis-flink-etl/)]

### Data Serving

#### SQL Data Modeling

* [ ] Building a sql data model for a music company in Postgres
* [ ] Build a Star Schema based Data Model in Postgres on the AirBnB dataset [[source code](04-serving/lab-airbnb-postgres-datamodel/)]
* [ ] Car company Data Model in MySQL [[source code](04-serving/lab-cars-mysql-datamodel/)]
* [ ] Create a star schema from 3NF schema on DVD rental Pagila dataset [[source code](04-serving/lab-dvd-rental-datamodel/)]
* [ ] Create a Postgres data model of Google Playstore dataset [[source code](04-serving/lab-google-playstore-datamodel/)]
* [ ] Inegi Snowflake Data Model [[source code](04-serving/lab-inegi-snowflake-datamodel/)]
* [ ] Northwind Data Model in MySQL [[source code](04-serving/lab-mysql-northwind-datamodel/)]
* [ ] Retail Store Data Model in MySQL [[source code](04-serving/lab-mysql-retail-store-datamodel/)]
* [ ] Creating a Bus Rapid Transit (BRT) Database in Postgres [[source code](04-serving/lab-postgres-busrapid-transit/)]
* [ ] Create Fact and Dimension Tables from Denormalized Raw Data [[source code](04-serving/lab-postgres-elt-datamodel/)]
* [ ] Postgres e-Wallet Data Model [[source code](04-serving/lab-postgres-ewallet-datamodel/)]
* [ ] Housing Data Model with CDC and SCD Type 2 [[source code](04-serving/lab-postgres-housing-cdc-scd/)]
* [ ] Credit Debit Finance Data Model in Snowflake [[source code](04-serving/lab-snowflake-creditdebit-datamodel/)]
* [ ] Sparkify Music Company Data Model in Postgres [[source code](04-serving/lab-sparkify-data-model-postgres/)]

#### NoSQL Data Modeling

* [ ] Building a nosql data model for a music company in Cassandra
* [ ] Create a NoSQL Data Model for a Digital Music Library using Cassandra [[source code](02-storage/datalakes/lab-adl-securing-monitoring-lakes/)]
* [ ] Create a NoSQL Data Model for an Email System using Cassandra [[source code](04-serving/cassandra-email-data-model/)]
* [ ] Create a NoSQL Data Model for Hotel Reservations using Cassandra [[source code](04-serving/cassandra-hotel-reservations/)]
* [ ] Create a NoSQL Data Model for Investment Accounts or Portfolios using Cassandra [[source code](04-serving/cassandra-investment-data-model/)]
* [ ] Create a NoSQL Data Model for Temperature Monitoring Sensor Networks using Cassandra [[source code](04-serving/cassandra-sensor-data-model/)]
* [ ] Create a NoSQL Data Model for Online Shopping Carts using Cassandra [[source code](04-serving/cassandra-shopping-cart-data-model/)]
* [ ] Ingest Movies data into CouchDB database [[source code](02-storage/nosql-databases/couchdb/lab-couchdb-movies-data-migration/)]

#### Visualization

* [ ] Streaming Analytics and Dashboards - Connect to a BigQuery data source, Create reports and charts to visualize BigQuery data [[source code](08-visualization/looker-studio/lab-gcp-streaming-analytics.md/)]

### Data Extraction

#### API

* [ ] archive.org [[source code](03-processing/pubsub/lab-gcp-pubsub.md/)]
* [ ] dummyjson [[source code](05-extraction/api/lab-dummyjson/)]
* [ ] exchangerates [[source code](05-extraction/api/lab-exchangerates/)]
* [ ] coinmarketcap [[source code](05-extraction/api/lab-extract-coinmarketcap/)]
* [ ] opennotify [[source code](05-extraction/api/lab-extract-opennotify/)]
* [ ] git [[source code](05-extraction/api/lab-processing-rest-payloads-git/)]
* [ ] saveonfoods [[source code](05-extraction/api/lab-saveonfoods/)]
* [ ] twitter [[source code](05-extraction/api/lab-twitter/)]
* [ ] datausa [[source code](05-extraction/api/lab-uspopulation/)]
* [ ] git and Hacker News [[source code](05-extraction/api/lab-hackernews-git-api/)]

#### Faker

* [ ] Extract synthetic data using Faker library in python [[source code](05-extraction/faker/lab-generate-data-with-faker/)]

#### Scraping

* [ ] Extract data using Web Scraping from Finance websites [[source code](05-extraction/webscraping/lab-finance-extract-load/)]

### Data Pipelines

* [ ] Getting started with Airflow [[source code](06-orchestration/airflow/lab-airflow-getting-started/)]
  * [ ] Install Airflow in local system
  * [ ] Starting Airflow Web server and Scheduler
  * [ ] Building a BASH commands execution pipeline in Airflow
  * [ ] Building a CSV to JSON pipeline in Airflow
* [ ] Integrate email notifications in Airflow with AWS SNS/SES service [[source code](06-orchestration/airflow/lab-airflow-email-notifications/)]
* [ ] Copying BigQuery Tables Across Different Locations using Cloud Composer [[source code](02-storage/warehouses/bigquery/lab-gcp-bigquery-composer/)]
* [ ] Bike Sharing Service Data Pipeline using Cloud Composer [[source code](06-orchestration/airflow/lab-bike-sharing-service-pipeline/)]
* [ ] Forex ETL with Airflow [[source code](06-orchestration/airflow/lab-forex-etl/)]
* [ ] Building an Airflow ETL pipeline to pull NFT data from Github and store in SQLite database [[source code](06-orchestration/airflow/github-nft/)]
* [ ] IMDB Spark ETL [[source code](06-orchestration/airflow/lab-imdb-spark-etl/)]
  * [ ] Build a data pipeline that download data
  * [ ] Process it
  * [ ] Calculate the hight profit movies
  * [ ] Save the processed data into Postgres database
* [ ] Building Data Ingestion Pipelines using Azure Data Factory [[Source code](06-orchestration/azure-data-factory/lab-data-ingestion-pipeline/)]
  * [ ] This lab covers ingesting data using Azure Data Factory and copying data between Azure SQL Database and Azure Data Lake
  * [ ] Recipe 1 - Provisioning Azure Data Factory
  * [ ] Recipe 2 - Copying files to a database from a data lake using a control flow and copy activity
  * [ ] Recipe 3 - Triggering a pipeline in Azure Data Factory
  * [ ] Recipe 4 - Copying data from a SQL Server virtual machine to a data lake using the Copy data wizard
* [ ] Incremental Data Loading using Azure Data Factory [[Source code](06-orchestration/azure-data-factory/lab-adf-incremental-loading/)]
  * [ ] This lab covers various methods to perform data loading in incremental fashion
  * [ ] Recipe 1 - Using Watermarking
  * [ ] Recipe 2 - Using File Timestamps
  * [ ] Recipe 3 - Using File partitions and folder structures
* [ ] Assignment - Build ETL Pipeline in Airflow using Toll data [[source code](06-orchestration/airflow/lab-tolldata/)]
* [ ] Develop Batch Processing Solution using Azure Data Factory [[Source code](06-orchestration/azure-data-factory/lab-batch-processing-solution/)]
  * [ ] In this lab, we design an end-to-end batch processing solution by using Data Factory, Data Lake, Spark, Azure Synapse Pipelines, PolyBase, and Azure Databricks
  * [ ] Recipe 1 - Data Ingestion using Data Flow
  * [ ] Recipe 2 - Data Transformation using Azure Databricks
  * [ ] Recipe 3 - Data Serving using PolyBase
  * [ ] Recipe 4 - Data Pipeline using Azure Data Factory Pipeline
  * [ ] Recipe 5 - End to end data processing with Azure Batch
* [ ] Building and Executing a Pipeline Graph with Data Fusion [[source code](06-orchestration/datafusion/lab-datafusion-pipeline/)]
* [ ] Prefect Getting Started [[source code](06-orchestration/prefect/lab-prefect-getting-started/)]
* [ ] Athena Query Orchestration with AWS Step Functions with SNS notifications [[source code](06-orchestration/stepfunctions/lab-stepfunction-athena-sns/)]
* [ ] AWS Step Functions and Amazon SQS to design and run a serverless workflow that orchestrates a message queue-based microservice [[source code](06-orchestration/stepfunctions/lab-stepfunction-ecomm-sqs/)]

### DevOps

* [ ] Introduction to Infra-as-code [[link to note](07-devops/infra-as-code.md/)]
* [ ] Introduction to Dockers [[link to note](07-devops/docker/)]
* [ ] Deploy docker in Amazon ECS [[source code](07-devops/ecs/lab-deploy-simple-docker-ecs/)]
* [ ] Create and managing Cloudformation stacks with AWS CLI [[source code](07-devops/cloudformation/)]
* [ ] Building your first FastAPI application [[source code](07-devops/fastapi/lab-simple-api/)]
* [ ] Building FastAPI application and Dockerize it [[source code](07-devops/fastapi/lab-simple-api-docker/)]
* [ ] FastAPI applications [[source code](07-devops/fastapi/)]
  * [ ] Online Academic Discussion Forum API
  * [ ] Online Book Reselling System API
  * [ ] Auction System
  * [ ] ERP System
  * [ ] Todo App
  * [ ] Task Planner System
  * [ ] Fitness Club Management System API
  * [ ] NewsStand Manegement System API
  * [ ] Poverty Analysis System API
  * [ ] Online Recipe System API
  * [ ] Online Restaurant Review System API
  * [ ] Intelligent Tourist System API
* [ ] FastAPI DevOps [[source code](07-devops/fastapi/lab-fastapi-devops/)]
  * [ ] Build and deploy a FastAPI
  * [ ] Serverless deploy using AWS's SAM framework
  * [ ] Use Cloudformation stack to automate the pipeline CICD
* [ ] Build and deploy NodeJS Kubia app in Kubernetes [[source code](07-devops/kubernetes/lab-kubernetes-kubia-app/)]
* [ ] Build Address parsing system in python and dockerize it [[source code](07-devops/docker/lab-assignment-etl-docker/)]

### Data Science & Machine Learning

* [ ] Basics of Regression and Classification models on Tabular data
* [ ] Getting started with NLP Deep Learning
  * [ ] Text Classification
  * [ ] Topic Modeling
  * [ ] Chatbots
  * [ ] Language Modeling
  * [ ] Named Entity Recognition
  * [ ] Text Clearning
  * [ ] Text Embedding
  * [ ] Text Generation
  * [ ] Text Similarity
  * [ ] Text Summarization
  * [ ] Transformers
  * [ ] Word2vec
* [ ] Getting started with Recommender Systems
  * [ ] Content-based
  * [ ] Collaborative
  * [ ] Hybrid
  * [ ] Session-based
  * [ ] Candidate Retrieval Model
  * [ ] Scoring and Ranking Model

#### Computer Vision

* [ ] Common Use Cases [[link to note](19-computer-vision/)]
  * [ ] Face Detection and Recognition
  * [ ] Image Classification
  * [ ] Image Similairty
  * [ ] Image Segmentation
  * [ ] Object Detection
  * [ ] Pose Estimation
  * [ ] Object Tracking
  * [ ] Scene Text Recognition
  * [ ] Video Classification
  * [ ] Video Action Recognition
* [ ] Video Classification Modeling with X3D Model [[source code](19-computer-vision/lab-video-classification/)]

### Capstones

* [ ] ACLED ETL Data Pipeline for war and conflict analysis (Airflow, Postgres, Glue, Spark) [[source code](12-capstones/acled/)]
* [ ] Sales & Orders ELT Data Pipeline (dbt, Redshift, SQL, Jinja) [[source code](12-capstones/dbt-redshift/)]
* [ ] Building End to end data pipeline in AWS [[source code](12-capstones/cloudmaze/)]
  * [ ] Activity 1: Ingestion with DMS
  * [ ] Activity 2: Data Lake Hydration
  * [ ] Activity 3: DMS Migration
  * [ ] Activity 4: Transforming data with Glue - Data Validation and ETL
  * [ ] Activity 5: Query and Visualize
* [ ] Funflix - Australian media company [[source code](12-capstones/funflix/)]
  * [ ] Design the data warehouse for Funflix
  * [ ] Build and deploy the data pipeline for Funflix's multi-region business
  * [ ] Build a data lake for the organization
* [ ] Datalake Schema Correction (AWS S3, Glue, Athena) [[source code](12-capstones/hmc/)]
* [ ] Kortex [[source code](12-capstones/kortex/)]
  * [ ] Design a data platform - MySQL (OLTP) and MongoDB (NoSQL)
  * [ ] Design and implement a data warehouse and generate reports from the data
  * [ ] Design a reporting dashboard that reflects the key metrics of the business
  * [ ] Extract data from OLTP, and NoSQL databases
  * [ ] Transform it and load it into the data warehouse
  * [ ] Create an ETL pipeline
  * [ ] Create a Spark connection to the data warehouse, and then deploy a machine learning model
* [ ] Movie Review Sentiment Analysis Pipeline [[source code](12-capstones/movie-sentiment/)]
* [ ] Building Recommender System from Scratch [[source code](12-capstones/recofront/)]
  * [ ] Front-end website built with Plotly Dash
  * [ ] Clickstream data collection using Divolte pipeline
  * [ ] Model building in python
  * [ ] Recommendation Serving
* [ ] Reddit Submissions, Authors and Subreddits analysis [[source code](12-capstones/reddit/)]
* [ ] Data Pipeline with dbt, Airflow and Great Expectations [[source code](12-capstones/robust-data-pipeline/)]
* [ ] Sparkify [[source code](12-capstones/spectrum/)]
  * [ ] SQL Data Modeling with Postgres
  * [ ] NoSQL Data Modeling with Cassandra
  * [ ] Data Lake with AWS and PySpark
  * [ ] Data Warehouse with Redshift
  * [ ] Data Pipeline with Airflow
* [ ] US Immigration analysis and data pipeline [[source code](12-capstones/us-immigration/)]
  * [ ] Data Load into S3
  * [ ] Data Preprocessing with PySpark
  * [ ] Data Modeling and Warehousing with Amazon Redshift
  * [ ] Advanced analytics using Python and Matplotlib
  * [ ] Convert the whole process into an airflow pipeline
* [ ] CitiBike Trip Histories Data Pipeline [[source code](12-capstones/citibike-trip-histories/)]
  * [ ] Build an end-to-end data pipeline
  * [ ] Cloud: GCP
  * [ ] Data Lake (DL): GCS
  * [ ] Data Warehouse (DWH): BigQuery
  * [ ] Infrastructure as code (IaC): Terraform
  * [ ] Workflow orchestration: Airflow
  * [ ] Transforming data: DBT
  * [ ] Data Visualization: Google Data Studio
* [ ] Global Historical Climatology Network Daily Data Pipeline [[source code](12-capstones/climate/)]
  * [ ] Build a global historical climatology network data pipeline that runs daily
  * [ ] Cloud: GCP
  * [ ] Infrastructure as code (IaC): Terraform
  * [ ] Workflow orchestration: Airflow (ingestion pipeline and transformation pipeline)
  * [ ] Data Warehouse: BigQuery
  * [ ] Data Lake: GCS
  * [ ] Batch processing/Transformations: dbt cloud or DataProc/Spark (transformation pipeline)
  * [ ] Dashboard: Google Data Studio
