# Rockbuster Stealth: Movies and Market Analysis
## Overview:
The project focused on Rockbuster Stealth - a fictional movie rental company that used to have stores around the world. 
The Rockbuster Stealth management team was planning to use its existing movie licenses to launch an online video rental service in order to stay competitive. 

## Objective: 
The project goal was to determine the most profitable movies and regions that should be prioritized when switching to the online platform.

## Data:
Rockbuster Stealth database contains information about the company’s movie inventory, customers, payments, and local stores.
The database has a snowflake schema, where dimension table is linked to other sub dimension tables that contain relational information.
It consists of 4 fact tables and 11 dimension tables. 

I used PostgreSQL to work with the database. 

## Analysis Process:
- Used Lucidchart application to extract Entity Relationshp Diagram to find out the database structure.
- Documented information about each table in a Data Dictionary (specified the columns type and description, marked primary and secondary keys).
- Replaced non-uniform data for rating column.
- Used aggregate functions to get a descriptive statistics for needed columns.
- Wrote cost-effective queries to filter, summarize, and sort data using the WHERE, GROUP BY, HAVING and ORDER BY clauses.
- Merged multiple tables using INNER JOIN and used common table expression to answer the business questions.
- Downloaded query result tables as Excel files and used them to build visualizations in Tableau.

## Results and Recommendations:
- Provided a list of movies that contributed the most to the company's revenue, along with the most profitable movie ratings, so the company can extend license for this categories.
- Defined top-3 popular genres (Sports, Sci-Fi and Animation) and identified the least popular one - Thriller.
- Advised to prioritize Asia, North and South America regions when launching the online platform, as they showed the highest sales.
- Drew attention to the countries with only one customer (almost 40% of the market) and recommended to analyze them further to find the reason behind low popularity.
- Provided a list of the most loyal customers and recommended to introduce special rates or rewards for them to motivate rent more movies.

## Project Deliverables:
- PowerPoint presentation
- Excel file with SQL queries
- Data dictionary 
- Dashboard on Tableau Public (All personal identifiable information was fabricated for the learning purposes, so publishing it online doesn't break the data privacy)
