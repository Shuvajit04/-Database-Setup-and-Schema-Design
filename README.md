# -Database-Setup-and-Schema-Design
📘 How I Made the Library Management System Database
✅ Tools Used:
I used MySQL Workbench to design and build the database.

🔧 Steps I Followed:
Created the Database
I ran this:
//code
CREATE DATABASE LibraryDB;
USE LibraryDB;

Identified the Entities
I chose Books, Authors, Categories, Members, Loans, and BookAuthors.

Created Tables
I wrote CREATE TABLE statements for each entity.

Added Primary Keys
I used AUTO_INCREMENT fields like BookID, AuthorID, etc., as primary keys.

Defined Foreign Keys
I set up foreign keys to link tables and maintain relationships.
Example: CategoryID in Books references Categories.

Created ER Diagram
I used the EER Diagram tool in MySQL Workbench to visualize the schema.

Viewed and Verified
I used commands like SHOW TABLES;, DESCRIBE Books;, and SELECT * FROM Books; to test the setup.
