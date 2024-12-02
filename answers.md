# Assignment Questions and Answers

## 1. State and Explain the components of a DBMS (Database Management System)
A DBMS has the following components:

- **Hardware**: Physical devices used to store and run the database, such as servers, storage devices, and networks.
- **Software**: The DBMS software itself, which includes the database engine, query processor, and tools for managing data.
- **Data**: The raw facts and information stored in the database.
- **Procedures**: Guidelines and instructions for users to manage and use the database effectively.
- **Database Access Language**: Tools like SQL that enable users to interact with the database.
- **Users**: The individuals or applications that interact with the DBMS, such as database administrators, developers, and end-users.

---

## 2. What is a relational database? Give 4 examples.
A relational database is a type of database that organizes data into tables (relations) with rows and columns, enabling easy access and management through structured query language (SQL).

**Examples**:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

---

## 3. State and Explain three classifications of SQL
1. **Data Definition Language (DDL)**: Commands used to define the structure of a database, such as creating, altering, and deleting tables.
   - Example: `CREATE`, `ALTER`, `DROP`.

2. **Data Manipulation Language (DML)**: Commands used to manipulate data within the database.
   - Example: `INSERT`, `UPDATE`, `DELETE`, `SELECT`.

3. **Data Control Language (DCL)**: Commands that control access to data and database objects.
   - Example: `GRANT`, `REVOKE`.

---

## 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for each record in a table. It ensures that no two rows have the same value.
  - Example: `StudentID` in a `Students` table.

- **Foreign Key**: A field in one table that references the primary key of another table, establishing a relationship between the two tables.
  - Example: `CourseID` in a `Enrollments` table referencing `CourseID` in a `Courses` table.

---

## 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the data, entities, and their relationships in a database. It is used during database design to map out the structure and interconnections between tables.

---

## 6. What are the advantages of relational databases?
1. **Data Integrity**: Maintains accuracy and consistency of data.
2. **Ease of Use**: Simplified querying using SQL.
3. **Scalability**: Supports large datasets with indexing and efficient storage.
4. **Flexibility**: Easy to modify and extend the schema.

---

## 7. State four types of data types used to store data in tables
1. **Integer**: Stores whole numbers (e.g., `INT`, `SMALLINT`).
2. **String**: Stores text data (e.g., `VARCHAR`, `CHAR`).
3. **Date/Time**: Stores date and time values (e.g., `DATE`, `DATETIME`).
4. **Boolean**: Stores logical values (e.g., `TRUE`, `FALSE`).

---

## 8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to provide a systematic way to store, retrieve, and manage data in a secure and efficient manner. It simplifies data handling by offering tools for organization, querying, and ensuring data consistency and integrity.

---


