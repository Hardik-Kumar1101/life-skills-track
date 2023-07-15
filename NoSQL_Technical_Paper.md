## 5 NoSQL Databases And Why They Are Used.

### What is NoSQL?
* NoSQL can also said as NO SQL or Not Only SQL.
* It is used when we need to store large amount of data.
* It is better readable and more scalable than RDBMS.

### Why NoSQL?
* Due to increase in digital interaction between the enterprises.
* The new enterprise technology architecture needs to be far more agile than ever before, and requires an approach to real-time data management that can accommodate unprecedented levels of scale, speed, and data variability.
* NoSQL databases are built to be flexible, scalable, and capable of rapidly responding to the data management demands of modern businesses. 

### Types of NoSQL Databases

#### Key Value Database
* Key-value stores are the least complex of the NoSQL databases.
* They are, as the name suggests, a collection of key-value pairs.
* ![Image for Key Value Pair](https://user-images.githubusercontent.com/95225089/183360583-a408d21c-83c4-4d81-bcb6-862366d1c38c.png)
* Examples of key-value stores are Redis, Voldemort, Riak, and Amazon’s Dynamo.

#### Document Database
* Document stores are one step up in complexity from key-value stores: a document store does assume a certain document structure that can be specified with a schema.
* ![Image for document database](https://user-images.githubusercontent.com/95225089/183365707-83fd9e0f-bcfb-4e27-91c4-314c870f0967.png)
* Examples of document stores are MongoDB and CouchDB.

#### Column Oriented Database
* These are NoSQL databases built for highly analytical, complex-query tasks. Unlike relational databases, columnar databases store their data by           columns, rather than by rows. These columns are gathered to form subgroups.

    The keys and the column names of this type of database are not fixed.
* ![Image for column database](https://user-images.githubusercontent.com/95225089/183368781-065bf412-07a1-4208-b1a4-0d2b213bdf62.png)
* Examples of column-family stores are Apache HBase, Facebook’s Cassandra, Hypertable.

#### Graph Database
* The last big NoSQL database type is the most complex one, geared toward storing relations between entities in an efficient manner. When the data is highly interconnected, such as for social networks, scientific paper citations, or capital asset clusters, graph databases are the answer. Graph or network data has two main components:

    Node—: The entities themselves. In a social network this could be people.

    Edge: The relationship between two entities. This relationship is represented by a line and has its own properties. An edge can have a direction, for             example, if the arrow indicates who is whose boss. 
 * ![Image for graph database](https://user-images.githubusercontent.com/95225089/183368089-0dc10ac3-86f1-456e-8fa2-fb028320393d.png)
 * Neo4j is the most popular graph database in use.
 ### Apache Cassandra
 * Apache Cassandra is a highly scalable, high-performance distributed database designed to handle large amounts of data across many commodity servers,      providing high availability with no single point of failure.
 * Apache Cassandra is a Column-Oriented Database.
 * Apache Cassandra, enables organisations to process large volumes of fast moving data in a reliable and scalable way. That's why companies like            Facebook, Instagram and Netflix use Apache Cassandra for mission-critical features.
 * ![image](https://user-images.githubusercontent.com/95225089/183370774-84bccb1f-7ab4-4894-b6d8-c0d27bf340fb.png)
  
### References
* [Difference Between RDBMS and NoSQL](https://www.geeksforgeeks.org/difference-between-relational-database-and-nosql/)
* [Use Of NoSQL](https://www.couchbase.com/resources/why-nosql)
* [Types of Databases](https://dzone.com/articles/nosql-database-types-1)
* [Apache Cassandra](https://www.tutorialspoint.com/cassandra/cassandra_introduction.htm)

