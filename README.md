#Library management System-Internship Task

This repository contains the "Database Schema" and "ER Diagram" for a Library management schema developed as a part of my internship task.

#Database Schema
 --Books (BookId[PK], Title, Author, YearPublished)
 --Members (MemberId[PK], Name, Email)
 --BorrowRecords (RecordID[PK], BookId[FK], MemberID[FK], BorrowDate, ReturnDate)
The schema is available in schema.sql.

#ER Diagram
The ER diagram representing the relationships between the tables is in ER Diagram.png.
