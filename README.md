# Fetch Rewards Coding Exercise - Data Analyst

This was a coding exercise given by Fetch rewards. I was given three datasets receipts.json, brands.json, and users.json. All the datasets were in json format. I have answered all the questions that were asked in the exercise.

1. The first part was to to review the unstructured JSON data and diagram a new structured relational data model. For this, I have included a screenshot of a structured ER diagram. Apart from this, I have also converted and tranformed these json files to structured dataframe using python. After converting these files, I have performed data cleaning and preprocessing like exploding some attributes, converting date to datetime format etc on these three datasets. I have uploaded the python notebook as well.

2. The second part was to write SQL queries to answer some of the questions from business stakeholders. For this, I installed necessary libraries and used  SQLite through SQL Alchemy in python to implement the queries. First I created a database called fetch in which I pushed all the three tranformed datasets and then I answered the queries that were asked using SQL.

3. The third part was to evaluate Data Quality Issues in the Data Provided. For this, I used SQL and python both to find the data quality issues. Some of   the issues that I found are:
   a) The primary key in the Receipt table is not unique
   b) The count of unique brand codes in the receipt and brand table does not match
   c) For some of the records in the brand table, attribute brand name and brandcode are same.

4. The fourth part was to communicate with Business Stakeholders. I have included a file where I wrote an email to Stakeholders to explain them my work and help them understand more about this data.
