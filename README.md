# Data Modeling with Cassandra

This is my second project in the Udacity Data Engineering Nanodegree, where I will be working with Apache Cassandra to model and analyze data. The project involves creating a database for a music streaming app called Sparkify.

## Introduction

Sparkify wants to analyze the data they have collected on songs and user activity on their music streaming app. They are particularly interested in understanding what songs users are listening to. Currently, the data resides in a directory of CSV files, making it difficult to query and generate the desired results.

My role in this project is to create an Apache Cassandra database that can handle queries on song play data and provide the necessary results to the analytics team at Sparkify.

## Project Overview

To complete this project, I will apply my knowledge of data modeling with Apache Cassandra and build an ETL (Extract, Transform, Load) pipeline using Python. The project involves modeling the data by creating tables in Apache Cassandra and then processing and inserting the data into these tables.

### Datasets

For this project, I will be working with the event_data dataset. The dataset consists of CSV files that are partitioned by date. Here are examples of filepaths to two files in the dataset:

- event_data/2018-11-08-events.csv
- event_data/2018-11-09-events.csv

### Project Template

To get started, I will use the provided project template, which includes a Jupyter Notebook file. The notebook will guide me through the steps required to complete the project. It already contains the necessary imports and provides a structure for the ETL pipeline.

The project template will help me:
- Process the event_datafile_new.csv dataset to create a denormalized dataset
- Model the data tables based on the queries that need to be answered
- Write the necessary Apache Cassandra statements for creating tables and inserting data
- Load the data into the tables and run the required queries

## Project Steps

To successfully complete this project, I will follow these steps:

1. Model the Apache Cassandra database: I will design tables to answer the queries outlined in the project template. This involves creating the keyspace, defining the tables, and specifying the primary keys and clustering columns.

2. Build the ETL pipeline: I will process the event data files and create a denormalized dataset. Then, I will write the Apache Cassandra statements to create tables and insert the processed data into the tables.

3. Test the database: I will run the provided queries on the Apache Cassandra database to ensure that the tables and data are correctly modeled and the queries return the expected results.

## Conclusion

By completing this project, I will gain hands-on experience in data modeling with Apache Cassandra and learn how to build an ETL pipeline using Python. I am excited to dive into the project and apply my knowledge to create an efficient and effective database for Sparkify.