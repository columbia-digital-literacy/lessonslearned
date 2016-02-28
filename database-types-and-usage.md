A database management system (DBMS) is a software application that interacts with the user, other applications, and the database itself to capture and analyze data.

Types

Relational databases are common - SQL being the most popular.
NoSQL is just lack of SQL, it's not a type in itself but a category.
NoSQL databases are often very fast, do not require fixed table schemas, avoid join operations by storing denormalized data, and are designed to scale horizontally. 
The most popular NoSQL systems include MongoDB, Couchbase, Riak, Memcached, Redis, CouchDB, Hazelcast, Apache Cassandra and HBase which are all open-source software products.

XML databases are a type of structured document-oriented database that allows querying based on XML document attributes. 
XML databases are mostly used in enterprise database management, where XML is being used as the machine-to-machine data interoperability standard.

Usage

Key-value (Ex. Redis) - Best used for top 10 lists etc. Faster than SQL for quickly retrieving records, but usually used on top of SQL, not by itself

Big table (Ex. Cassandra) - Split data into smaller computers and store tons of streaming / real time data (Ex. twitter firehose). 
Hadoop also lets us split query across computers and parallelize problems

Graph DB (Ex. Facebook search, google knowledge graph) - Keeps track of nodes and edges, especially useful for tracking social relationships, adds a layer of data intelligence

Document Data - (Ex. MongoDB) - Only stores data, doesn't send success response. This saves time, but doesn’t assure 100% accuracy. On the whole, more flexible than sql

In recent years there was a high demand for massively distributed databases with high partition tolerance but according to the CAP theorem it is impossible for a distributed system to simultaneously provide consistency, availability and partition tolerance guarantees. 
A distributed system can satisfy any two of these guarantees at the same time, but not all three. For that reason many NoSQL databases are using what is called eventual consistency to provide both availability and partition tolerance guarantees with a reduced level of data consistency.

Time series databases - http://techcrunch.com/2016/02/19/optimizing-analytics-on-time-series-databases-a-supply-chain-perspective/

NewSQL is a class of modern relational databases that aims to provide the same scalable performance of NoSQL systems for online transaction processing (read-write) workloads while still using SQL and maintaining the ACID (Atomicity, Consistency, Isolation, and Durability) guarantees of a traditional database system.
Such databases include ScaleBase, Clustrix, EnterpriseDB, MemSQL, NuoDB and VoltDB.
These new generation of databases such as NuoDB (SQL + graph) allow for a combination of usage functions.
