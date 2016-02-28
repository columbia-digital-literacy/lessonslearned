#Big data overview!
There are many factors to consider when deciding which type of data storage and analytical options are best for your business:
- Size
- Type of data (e.g., CSV, JSON, YAML)
- Schema (e.g., relational vs. graph)
- Frequency of analytical requirements (e.g., real time vs batch)
- And wayyy more than that

Over time, there have been 4 broad "big data" options:
- SQL DB instances: Able to store and retrieve large amounts of structured data.
    - A business might use this standard option used for back end storage of important information on their users, such as account login information, user event data. 
    - This is also a viable option if the business does not need to retrieve and analyze large amounts of this data very rapidly. Within this category, there are different options, such as postgre SQL, that are favorable depending on the schema flexibility requirements. 
    - Note that MongoDB is an example of a NoSQL DB, ideal for unstructured data. 
    
- Hadoop: Able to store and retrieve much larger amounts of data
    -When SQL just isn't enough, you need Hadoop. Instead of storing your data in one instance, Hadoop stores the data across multiple
      clusters that are optimized to process large queries. 
    
- Kafka/Storm: Able to retrieve data "streams" in near-real time
    - When Hadoop just can't keep up with your processing requirements (gotta read those Tweets now!), it's time to start thinking about Kafka/Storm. To make your data project more efficient, check out Apache Spark to unify Hadoop, Kafka, and Storm
      
      
- Graph DB: Able to store and analyze "graph" data
  If you're working with nodes, connections, edges, etc., all of the above options aren't going to cut it.
  
[Here's a link to find out more info!](http://www.information-age.com/technology/information-management/123460615/top-8-trends-big-data-2016)
  
![Hadoop elephant](http://siliconangle.com/files/2014/12/hadoop-elephant.png)
