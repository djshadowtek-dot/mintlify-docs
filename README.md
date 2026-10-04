# Comprehensive Glossary of Essential Tech & Data Concepts

Welcome to this easy-to-read database of core terminologies spanning databases, computer science, and data structures. This guide simplifies complex jargon into straightforward, scannable definitions.

---

## Database Concepts

### 1. Data Base (DB)
- Definition: An organized collection of structured information, or data, stored electronically in a computer system.
- Key Detail: Databases are usually controlled by a Database Management System (DBMS).
- Analogy: A digital filing cabinet designed for rapid searching and retrieval.

### 2. Relational Database Management System (RDBMS)
- Definition: A type of database management system that stores data in tables (rows and columns) that are linked—or related—to other tables.
- Key Detail: Relational databases use Structured Query Language (SQL) to create, read, update, and delete data.
- Examples: MySQL, PostgreSQL, Oracle, Microsoft SQL Server.

### 3. Non-Relational Database (NoSQL)
- Definition: A database that stores data in formats other than traditional tables, such as documents, key-value pairs, wide-columns, or graphs.
- Key Detail: NoSQL databases are highly scalable and flexible, making them ideal for unstructured or rapidly changing data.
- Examples: MongoDB (document), Redis (key-value), Cassandra (wide-column), Neo4j (graph).

### 4. Schema
- Definition: The blueprint or logical structure that defines how data is organized within a database.
- Key Detail: In an RDBMS, the schema dictates the tables, fields, data types, and relationships between them.

### 5. Primary Key
- Definition: A unique identifier for a specific record (row) within a database table.
- Key Detail: A primary key value can never be duplicated, and it cannot be empty (Null).
- Example: A unique Student ID number in a school database.

### 6. Foreign Key
- Definition: A field in one database table that links to the Primary Key of another table.
- Key Detail: Foreign keys are used to establish and enforce links (relationships) between the data in two different tables.

### 7. Index
- Definition: A data structure used by databases to quickly locate and access data without having to search every row in a table.
- Key Detail: While indexes significantly speed up data retrieval (SELECT queries), they can slow down data writes (INSERT/UPDATE) because the index must also update.

### 8. Transaction & ACID Properties
- Definition: A single logical unit of database work that contains one or more operations.
- Key Detail: To ensure data integrity, database transactions must follow the ACID rules:
  - Atomicity: The entire transaction succeeds, or none of it does (all-or-nothing).
  - Consistency: The database transitions from one valid state to another valid state.
  - Isolation: Concurrent transactions do not interfere with each other.
  - Durability: Once a transaction is committed, it remains saved even during a power crash.

### 9. Normalization
- Definition: The process of structuring a relational database to reduce data redundancy and improve data integrity.
- Key Detail: It involves splitting large, messy tables into smaller, well-defined ones and linking them using relationships.

---

## Fundamental Computing & Architecture

### 1. API (Application Programming Interface)
- Definition: A set of rules and protocols that allows different software applications to communicate and exchange data with one another.
- Key Detail: An API acts as a middleman, delivering your request to a provider and bringing the response back to you.
- Analogy: A waiter in a restaurant who takes your order to the kitchen and brings your food back.

### 2. Client-Server Architecture
- Definition: A computing model where tasks are split between service providers (servers) and service requesters (clients).
- Key Detail: The Client (for example, your web browser) sends a request, and the Server (for example, a computer hosting a website) processes that request and sends back a response.

### 3. Cloud Computing
- Definition: The delivery of computing services—including servers, storage, databases, networking, and software—over the Internet (the cloud).
- Key Detail: Instead of buying and maintaining physical data centers, companies rent access to these resources from cloud providers like AWS, Microsoft Azure, or Google Cloud.

---

## Data Structures

### 1. Array
- Definition: A collection of items stored at contiguous memory locations, where each item can be accessed using an index number.
- Key Detail: Arrays usually have a fixed size, meaning you cannot easily add more elements once they are full.

### 2. Linked List
- Definition: A linear collection of data elements called nodes, where each node points to the next node in the sequence.
- Key Detail: Unlike arrays, linked lists do not store items in adjacent memory locations, making them highly flexible for adding or removing items dynamically.

### 3. Stack
- Definition: A data structure that follows the LIFO (Last In, First Out) principle.
- Key Detail: The last item added to the stack is the first one to be removed.
- Analogy: A stack of physical plates in a cafeteria.

### 4. Queue
- Definition: A data structure that follows the FIFO (First In, First Out) principle.
- Key Detail: The first item added to the queue is the first one to be processed and removed.
- Analogy: A line of people waiting to buy tickets at a cinema.

### 5. Hash Table
- Definition: A data structure that stores data as key-value pairs for fast lookup.
- Key Detail: A hash function converts a key into an index used to locate the stored value.
- Common Uses: Caching, dictionaries, symbol tables.

### 6. Tree
- Definition: A hierarchical data structure with a root node and child nodes.
- Key Detail: Trees are useful for representing parent-child relationships and organizing data efficiently.
- Common Types: Binary tree, AVL tree, B-tree.

### 7. Graph
- Definition: A structure made up of nodes and edges that connect them.
- Key Detail: Graphs are used to model networks, relationships, maps, and dependency structures.
- Examples: Social networks, maps, recommendation systems.

---

## Summary

This glossary gives you the core building blocks of modern software and data systems. If you understand these concepts, you will be well-prepared for databases, software design, system architecture, and programming interviews.

