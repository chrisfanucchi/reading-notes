# Reading: Class 11 - Mongo and Mongoose

## NoSQL vs SQL

Fill in the chart below with five differences between SQL and NoSQL databases:

|         SQL         |            NoSQL             |
| :-----------------: | :--------------------------: |
|     relational      |        non-relational        |
|     table-based     |  key-value, document-based   |
|  predefined schema  | dynamic schema, unstructured |
| vertically-scalable |    horizontally-scalable     |
| structured queries  |     unstructured queries     |
|                     |                              |

1. What kind of data is a good fit for an SQL database?

   SQL is good when you will have complex queries, with heavy duty transactions.

2. Give a real world example.

   SQL is great for use with inter-relational, table based data, where queries must interact with the various table relationships (e.g. complex customer DBs with inter-related sales, CRM, financial, etc. data).

3. What kind of data is a good fit a NoSQL database?

   NoSQL is good when using large datasets.

4. Give a real world example.

   NoSQL works great when the dataset or data inter-relationships are not very complex, but there are large amount of simply-stored data (e.g. data warehouses, large data analytics, etc.)

5. Which type of database is best for hierarchical data storage?

   NoSQL

6. Which type of database is best for scalability?

   - SQL is scaled by increasing the server's "horse power" (e.g. CPU, memory, etc.)
   - NoSQL is scaled by added more servers "in parallel"

## SQL vs NoSQL

1. What does SQL stand for?

   Structured Query Language

2. What is a relational database?

   A SQL DB with inter-related tables of data

3. What type of structure does a relational database work with?

   Table structure, that may be inter-related.

4. What is a ‘schema’?

   A schema defines what can go in fields.

5. What is a NoSQL database?

   A DB that is not based on a structured query language methodology or imposed schema, with no or few inter-relationships.

6. How does it work?

   Data is stored in collections and then documents, instead of tables.

7. What is inside of a Mongo database?

   It is a NoSQL DB, named for being "humongous,"

8. Which is more flexible - SQL or MongoDB? and why.

   It depends on the type of application and data being stored. SQL DBs are good for complex, predictable datasets that might benefit from using a schema. On the other hand, MongoDBs (NoSQL) are great for large, simplistic data stores, with a large/numerous read or writes, and minimal inter-relationships.

9. What is the disadvantage of a NoSQL database?

   There can be the storing of redundant data to minimize relationality between data collections, requiring the need to update the same data in multiple collections.

## Things I want to know more about

Why are we focusing on non-SQL-based DBs in this class?
