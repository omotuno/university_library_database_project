# University Library Database

This project designs and implements a relational database for a university library system to track books, authors, publishers, students, and employees.

The database schema consists of the following tables:
<img width="806" alt="Screenshot 2023-12-10 at 4 51 21 PM" src="https://github.com/omotuno/university_library_database_project/assets/65866718/05509371-3eaa-4ca1-9442-911a0a3aa8eb">

BOOK - Contains book ID, name, page count, ISBN, and foreign keys

AUTHOR - Stores author ID, name, address, and email

PUBLISHER - Stores publisher ID, name, address, and email

STUDENT - Stores student ID, name, address, and email

EMPLOYEE - Stores employee ID, name, address, and email

BOOK_AUTHOR - Mapping table for books and authors


## Key constraints and relationships:

Primary keys on ID fields for each main entity table

Foreign keys from BOOK to STUDENT, EMPLOYEE, and PUBLISHER

Mapping table BOOK_AUTHOR for many-to-many relationship between books and authors

**The database is implemented in SQL using MariaDB Server and HeidiSQL**. 

Table creation statements and sample insert statements are included for testing. Stored procedures could be added to encapsulate logic and enable easy querying.

This database provides a way to store, track, and query all key entities and relationships for the university library system.
