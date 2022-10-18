# Crowdfunding ETL

## Summary

In this project we **extract** data from a variety of CSV files, review and **transform** their contents, then build an Entity Relationship Diagram (ERD) which we use to export a schema for PostgresSQL. From there, we **load** our CSV files into the SQL database and write queries that allow us to join tables based on their relationships to each other, as well as establish how many campaigns still have not met their fundraising goals. Finally, we export new CSVs that include first name, last name and email addresses for fundraiser contacts and backers.

![Entity Relationship Diagram](https://github.com/bristlab/Crowdfunding-ETL/blob/main/crowdfunding_db_relationships.png?raw=true)

![pgAdmin Backers](https://github.com/bristlab/Crowdfunding-ETL/blob/main/pgAdmin_backers.png?raw=true)
