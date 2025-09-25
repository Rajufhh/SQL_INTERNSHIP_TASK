

-----------------------------------------------------------TASK -1 ------------------------------------------------------

# Library Management System Database

## Overview
This project is a **relational database schema** for a Library Management System. It manages books, authors, publishers, categories, members, staff, and borrowing transactions.

## Features
- Track **books**, their **authors**, **publishers**, and **categories**.
- Manage **library members** and **staff**.
- Record **borrow and return transactions**.
- Enforces **data integrity** using primary & foreign keys.
- Supports **cascading updates and deletes** to maintain consistency.

## Tables
- **Author**: AuthorID, Name, Country  
- **Publisher**: PublisherID, Name, Address  
- **Category**: CategoryID, CategoryName  
- **Book**: BookID, Title, ISBN, CopiesAvailable, AuthorID, PublisherID, CategoryID  
- **Member**: MemberID, Name, Email, Phone  
- **Staff**: StaffID, Name, Role  
- **Borrow**: BorrowID, MemberID, BookID, StaffID, IssueDate, DueDate, ReturnDate  

## Special Features
- `AUTO_INCREMENT` for unique IDs.  
- `ON UPDATE CASCADE` and `ON DELETE CASCADE` for referential integrity.  
- Sample dataset provided for testing.

## How to Use
1. Create a MySQL database.  
2. Run the `CREATE TABLE` scripts.  
3. Insert sample data using the provided `INSERT` statements.  
4. Perform queries like finding borrowed books, overdue books, etc.

## Author
Raju Bathini







-----------------------------------------------------------TASK -2 ------------------------------------------------------



🗄️ Tables

Author → AuthorID, Name, Country

Publisher → PublisherID, Name, Address

Category → CategoryID, CategoryName

Book → BookID, Title, ISBN, CopiesAvailable, AuthorID, PublisherID, CategoryID

Member → MemberID, Name, Email, Phone

Staff → StaffID, Name, Role

Borrow → BorrowID, MemberID, BookID, StaffID, IssueDate, DueDate, ReturnDate

🌟 Special Features

AUTO_INCREMENT for unique IDs.

ON UPDATE CASCADE and ON DELETE CASCADE for referential integrity.

Includes sample dataset for testing.

🚀 How to Use

Create a MySQL database.

Run the CREATE TABLE scripts.

Insert sample data using provided INSERT statements.

Try queries like:

Find borrowed books

Check overdue books

List most borrowed categories

-----------------------------------------------------------TASK - 3 ------------------------------------------------------

Writing Basic SELECT Queries

Overview
This task focuses on practicing SQL commands for retrieving data from one or more tables. It demonstrates selecting all columns or specific ones, filtering rows with conditions, sorting results, and limiting the output.

Features
Select all columns or specific columns.

Filter rows using WHERE, AND, OR.

Perform pattern matching with LIKE.

Use BETWEEN for range filtering.

Sort results with ORDER BY (ascending/descending).

Limit the number of rows returned.

Retrieve unique values with DISTINCT.

Apply aliasing (AS) for readability.

Tables
Students:

RollNo (Primary Key)

Name

Age

City

Marks

Special Features
Supports selecting all (*) or specific columns.

Demonstrates filtering with operators (=, IN, BETWEEN, LIKE).

Shows both ascending and descending sorting.

Illustrates LIMIT for restricting output.

Explains aliasing (AS) and distinct results (DISTINCT).

Covers interview-style examples with practical queries.

How to Use
Create a database in MySQL/SQLite.

Run the CREATE TABLE script to create the Students table.

Insert sample data into the table.

Execute the provided SELECT queries one by one.

Observe the results for filtering, sorting, and limiting.


-----------------------------------------------------------------------------------------------




