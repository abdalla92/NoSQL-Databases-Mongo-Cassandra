# NoSQL Databases (MongoDB, Cassandra, Cloudant)
This project aims to use MongoDB, Cassandra and Cloudant skills to move data from one database type to another and run queries.

## Scenerio

A data engineer at a data analytics consulting company. the company prides itself in being able to efficiently handle data in any format on any database on any platform. Analysts in my office need to work with data on different databases, and data in different formats. While these analysts are good at analyzing data, they count on data engineers to be able to move data from external sources into various databases, to be able to move data from one type of database to another, and be able to run queries on various databases.

## Objectives
This project demonstrates to perform the following tasks:

  Import data into a MongoDB database.

  Query data in a MongoDB database.

  Export data from MongoDB.

  Import data into a Cassandra database.

  Query data in a Cassandra database.

  Export data from a Cloudant database

  Import data into a Cloudant database

  Replicate a Cloudant database

  Create indexes on a Cloudant database

  Query data in a Cloudant database

## Tasks 
### MongoDB
Import movies.json into the MongoDB server into an entertainment database and a movie collection.

Write a MongoDB query to find the year most movies were released.

Write a MongoDB query to find the count of movies released after the year 1999.

Write a query to determine the average votes for movies released in 2007.

Export selected fields from the movies collection into a file named partial_data.csv.

### Cassandra
Create a keyspace named entertainment.

Import partial_data.csv into a Cassandra server.

Write a CQL query to count the movie table's rows.

Create an index for the movie table's rating column using CQL.

Write a CQL query to count the number of movies that are rated "G."

### Cloudant
Export Cloudant data in CSV, JSONs formats and save to a file

Import data from json into your Cloudant Database

Replicate a local database into your Cloudant instance

Create indexes using HTTP API

Query data using HTTP API

