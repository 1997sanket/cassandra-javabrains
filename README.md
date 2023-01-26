Cassandra 

1. Distributed
2. NoSQL
3. Highly Available
4. Tunable Consistency 
5. Write Fast
6. Replication strategies and Partitioning:
    https://www.baeldung.com/cassandra-replication-partitioning.
7. Cassandra keys and Clustering columns:
    https://www.baeldung.com/cassandra-keys
8. CAP 
    -Consistency 
        -Mimicking single node db, like a RDBMS, data always being consistent.
        -Every user quering a data, will always get the same data.
    -Availability
        -Achieved by Replication of nodes
        -Even one node goes down in a datacenter, another node is still available.
    -Partition Tolerance
        -Data partitioning amongst node, and how they communicate.
        -Data base must keep on working even if there is some problem with a partition node.
        
 9. By Default Cassandra is "AP", but it has tunable consistency also.
