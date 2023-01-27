# Data-Modeling-with-Apache-Cassandra
## Sparkify - Data Modeling with Cassandra - Udacity Data Engineering Nanodegree 
----------------------------------------------------------------------------------
### Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.


-------------------------------------------------------------------------------------------------
### Project Description
In this project, I will apply what I've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, I model my data by creating tables in Apache Cassandra to run below queries.

* Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4

* Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182

* Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

---------------------------------------------------------------------------------------------
### Datasets
#### event_data:

For this project, I will  working with one dataset: event_data. The directory of CSV files partitioned by date.


------------------------------------------------------------------------------
### Files
* etl.ipynb
* event_datafile_new.csv

---------------------------------------------------------------------------------
### Steps
* Connect to Cassandra Database
* Create a keyspace
* Connect to that keyspace
* Create tables that will answer our queries 
* Insert data into those tables

------------------------------------------
