## 5 NoSQL Databases And Why They Are Used.

### What is NoSQL?
* NoSQL can also say as NO SQL or Not Only SQL.
* It is used when we need to store large amounts of data.
* It is better readable and more scalable than RDBMS.

### Why NoSQL?
* Due to the increase in digital interaction between enterprises.
* The new enterprise technology architecture needs to be far more agile than ever before and requires an approach to real-time data management that can accommodate unprecedented levels of scale, speed, and data variability.
* NoSQL databases are built to be flexible, scalable, and capable of rapidly responding to the data management demands of modern businesses. 

### Types of NoSQL Databases

#### Key-Value Database
* Key-value stores are the least complex of the NoSQL databases.
* They are, as the name suggests, a collection of key-value pairs.
* ![Image for Key Value Pair](https://user-images.githubusercontent.com/95225089/183360583-a408d21c-83c4-4d81-bcb6-862366d1c38c.png)
* Examples of key-value stores are Redis, Voldemort, Riak, and Amazon’s Dynamo.

#### Document Database
* Document stores are one step up in complexity from key-value stores: a document store does assume a particular document structure that can be specified with a schema.
* ![Image for document database](https://miro.medium.com/v2/resize:fit:720/format:webp/1*vhKORnX6ZQ5HNUaeqxbQGg.png)
* Examples of document stores are MongoDB and CouchDB.

#### Column-Oriented Database
* These are NoSQL databases built for highly analytical, complex-query tasks. Unlike relational databases, columnar databases store their data by           columns, rather than by rows. These columns are gathered to form subgroups.

    The keys and the column names of this type of database are not fixed.
* ![Image for column database](https://assets-global.website-files.com/620d42e86cb8ec4d0839e59d/6230f60beb40de5402e42afd_61c9dc6201b6e4d8debe7976_Columnar-Database-Diagram.png)
* Examples of column-family stores are Apache HBase, Facebook’s Cassandra, and Hypertable.

#### Graph Database
* The last big NoSQL database type is the most complex one, geared toward efficiently storing relations between entities. When the data is highly interconnected, such as for social networks, scientific paper citations, or capital asset clusters, graph databases are the answer. Graph or network data has two main components:

    Node—: The entities themselves. In a social network, this could be people.

    Edge: The relationship between two entities. This relationship is represented by a line and has its properties. An edge can have a direction, for             example, if the arrow indicates who is whose boss. 
 * ![Image for graph database](https://phoenixnap.com/kb/wp-content/uploads/2021/04/Graph-of-phoenixNap-network-locations.png)
 * Neo4j is the most popular graph database in use.
 ### Apache Cassandra
 * Apache Cassandra is a highly scalable, high-performance distributed database designed to handle large amounts of data across many commodity servers,      providing high availability with no single point of failure.
 * Apache Cassandra is a Column-Oriented Database.
 * Apache Cassandra, enables organizations to process large volumes of fast-moving data in a reliable and scalable way. Companies like            Facebook, Instagram, and Netflix use Apache Cassandra for mission-critical features.
 * ![image](https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2023/01/how-does-cassandra-work.webp?_gl=1*1oih0mu*_ga*NTM5NDg1NTcwLjE2ODk0ODYxNjM.*_ga_73N1QWLEMH*MTY4OTQ4NjE2Mi4xLjEuMTY4OTQ4NjE2Mi42MC4wLjA.&_ga=2.222404383.521560767.1689486166-539485570.1689486163)
  
### References
* [Difference Between RDBMS and NoSQL](https://www.geeksforgeeks.org/difference-between-relational-database-and-nosql/)
* [Use Of NoSQL](https://www.couchbase.com/resources/why-nosql)
* [Types of Databases](https://dzone.com/articles/nosql-database-types-1)
* [Apache Cassandra](https://www.tutorialspoint.com/cassandra/cassandra_introduction.htm)

