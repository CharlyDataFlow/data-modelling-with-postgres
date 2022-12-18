<b>Introduction</b>

A startup called <b>Sparkify</b> want to analyze the data they have been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to.

The aim is to create a Postgres Database Schema and ETL pipeline to optimise queries for song play analysis.

<b>Project Description </b>

Developed a relational database using PostgreSQL to model user activity data for a music streaming app. Skills include:
* Created a relational database using PostgreSQL
* Developed a Star Schema database using optimized definitions of Fact and Dimension tables. Normalization of tables.
* Built out an ETL pipeline to optimize queries in order to understand what songs users listen to.

Proficiencies include: Python, PostgreSql, Star Schema, ETL pipelines, Normalization

I have to use Python to create an ETL pipeline and Postgres to model data for this project. For a particular focus, I need to define fact and dimension tables for a Star Schema on the database side. On the other side, an ETL pipeline would use Python and SQL to transport data from files in two local directories into these Postgres tables.

<b>Schema for Song Play Analysis</b>

<b>Fact Table</b>

<b> songplays </b> records in log data associated with song plays

<b>Dimension Tables</b>

<b> users </b> in the app

<b> songs </b> in music database

<b> artists </b> in music database

<b> time: </b> timestamps of records in songplays broken down into specific units

<b>Project Design</b>

Because we can obtain the most information and do analysis with a small number of tables and appropriate joins, database design is highly optimized.

ETL Design is also made simpler. read json files and parse them appropriately to store tables in specified columns with the correct formatting.

<b>Database Script</b>

Writing "python create_tables.py" command in terminal, it is easier to create and recreate tables

<b>Jupyter Notebook</b>

The Jupyter notebook etl.ipynb is provided for checking each command and the data as well. Using these instructions, copy them into etl.py, execute them into the terminal by typing "python etl.py," and then run test.ipynb to check whether the data has been loaded in all the tables.

<b>Relevant Files Provided </b>

<b>test.ipnb </b>displays the first few rows of each table to let you check your database

<b>create_tables.py </b>drops and created your table

<b>etl.ipynb </b>read and processes a single file from song_data and log_data and loads into your tables in Jupyter notebook

<b>etl.ipynb </b>read and processes a single file from song_data and log_data and loads into your tables in ET

<b>sql_queries.py </b>containg all your sql queries and in imported into the last three files above