# Database Overview

## 1. Indexing
- **1.1 B-tree**: 
  - Description of B-tree indexing and its advantages in databases.
- **1.2 B+ tree**: 
  - Explanation of B+ tree indexing and how it improves data retrieval.

## 2. Transactions
- **2.1 ACID**: 
  - **Atomicity**: Ensures complete success or failure of transactions.
  - **Consistency**: Guarantees database integrity before and after transactions.
  - **Isolation**: Ensures that transactions occur independently.
  - **Durability**: Ensures that once a transaction is committed, it remains so.
  
- **2.2 Isolation Levels**:
  - **Read Committed**: Prevents dirty reads.
  - **Read Uncommitted**: Allows dirty reads.
  - **Repeatable Read**: Ensures consistent reads within a transaction.
  - **Serializable**: Provides strict isolation, simulating transactions running sequentially.

## 3. Locking Mechanisms
- **Permission Lock**: 
  - When to use permission locks for access control.
- **Optimistic Lock**: 
  - When to use optimistic locks for better concurrency without locking resources.

## 4. Cluster Key
- Explanation of what a cluster key is and its importance in database design.

## 5. SQL vs. NoSQL
- **SQL Databases**: MySQL, PostgreSQL
- **NoSQL Databases**: MongoDB
- **Choosing Between SQL and NoSQL**:
  - Factors to consider when selecting a database type.

## 6. Redis
- **Use Cases for Redis**: 
  - When to use Redis and the advantages it offers for caching and fast data retrieval.

## 7. Advanced Concepts
- **Vertical vs. Horizontal Scaling**: 
  - Definitions and use cases for each scaling method.
- **Replication**: 
  - Importance of data replication for redundancy and availability.
- **Load Balancing**: 
  - Techniques for distributing traffic across multiple servers.
- **Concurrency and Locking Mechanisms**: 
  - Overview of managing concurrent access to data.
- **Database Security and Permissions**: 
  - Best practices for securing databases.
- **Caching Strategies**: 
  - Techniques for improving database performance through caching.

## 8. Kafka and Message Queues
- Explanation of how Kafka works as a message queue and its role in data processing.

## 9. Distributed Locks
- Overview of distributed locking mechanisms and their applications.

## 10. Master and Replica Databases
- Explanation of master-slave architecture and its benefits for read scalability.
