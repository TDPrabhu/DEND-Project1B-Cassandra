### Introduction

In this Project we have extracted the data from all the event generated from the csv file and create a deformalized dataset 
event_datafile_new.csv.

Then model the data tables based on the queries which we need to execute.

Once the data tables are created based on the queries, we will load data in to the table created from event_datafile_new.csv.

### ETL PIPELINE

In the first section of the notebook, we have extracted the data from all the csv file generated and created a deformalized dataset.

In the next section comes the real picture, where we need to model the data tables based on the queries.

First we need to create the keyspace (sparkify_musicapp).

Then we need to model the data tables based on the queries. Need to pay attention on the data type, primary key, 
partition key, clustering key.

Need to make sure the data are made unique, so need to choose the columns carefully.

### Project structure
##### 1) /event_data - The directory of CSV files partitioned by date
##### 2) /images - Simply a folder with images that are used in Project_1B_ Project_Template notebook
##### 3) Project_1B_ Project_Template.ipynb - It is a notebook that explains the project step by step
##### 4) event_datafile_new.csv - The aggregated CSV composed by all event_data files, denormalized dataset.
