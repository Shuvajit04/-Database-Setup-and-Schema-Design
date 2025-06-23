# -Database-Setup-and-Schema-Design
📘 How I Created the Library Management System Database
To complete this task, I used MySQL Workbench as the database design tool. I began by creating a new database named LibraryDB using the CREATE DATABASE and USE commands. After choosing the Library Management System as the domain, I identified the key entities required: Books, Authors, Categories, Members, Loans, and a junction table BookAuthors to handle the many-to-many relationship between books and authors.

I then wrote CREATE TABLE statements for each of these entities. For each table, I defined a primary key using AUTO_INCREMENT fields such as BookID, AuthorID, and MemberID to uniquely identify each record. Next, I added foreign keys to define relationships between the tables—for example, CategoryID in the Books table references Categories, and the BookAuthors table links both BookID and AuthorID as foreign keys.

After setting up all the tables and relationships, I used SQL commands like SHOW TABLES, DESCRIBE Books, and SELECT * FROM Books to verify that everything was working as expected. Finally, I used the EER Diagram feature in MySQL Workbench to visually represent the schema and confirm that the relationships were correctly implemented.
