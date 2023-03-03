# Working with Semistructured Data in Snowflake
<br />
<br />

## Time
- 2 hours

### Description
This activity gives associates time to practice using semi-structured querying in Snowflake
<br />
<br />

### Main Goals
- Staging and loading data from semistructured files
- Practice querying data from colulmns containing semi-structured data
- Practice with Snowflake's datatypes that allow for semi-structured data (mainly, VARIANT)
<br />
<br/>

## Trainer Instructions
1. Create an activity that includes the following requirements:
    -	Stage files into Snowflake using the web application (Snowsight). One or some should have semi-structured data (JSON, XML)
    -	Start a virtual warehouse, create a schema, and create a table for your data to be inserted into
    -	COPY data from the staged file into your created table
    -	Query the data to find answers to a series of questions. The queries should be aimed at using columns that contain this semi-structured data
2. Here's an example of an activity:
    -	[movies.xml](../resources/movies.xml)
    -	1) Stage movies.xml into Snowflake
    -	2) Create VW/Schema
    -   3) Create a simple table with an ID column (primary key) and a 'movie' column
    -	4) Load data into this table using the COPY command. Each child elemennt of the root element should be in its own row
    -   5) Answer these questions:
		- List the movies that were released before 2000
		- List the movies who's genre is 'Crime'
		- Who is the oldest actor listed?

<br />
<br />

## Associate Instructions: 
1. Complete the given activity and be prepared to present your process/findings.
<br />
<br />
