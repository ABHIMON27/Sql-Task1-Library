# Sql-Task1-Library
Database Setup and Schema Design
✅ 2. Identified Entities and Relationships:
Entity	Attributes
Author	author_id, name, nationality
Book	book_id, title, genre, publication_year, author_id
Member	member_id, name, email, join_date
Loan	loan_id, book_id, member_id, issue_date, return_date
Publisher	publisher_id, name, country
Book_Publisher	book_id, publisher_id (Many-to-Many)
