# Library Management System – Internship Task

## Overview
This repository contains the **Database Schema** and **ER Diagram** for a Library Management System developed as part of my internship task. The focus is on creating a structured database with proper relationships between entities.

## Database Schema
- **Books** – `BookId` (PK), `Title`, `Author`, `YearPublished`  
- **Members** – `MemberId` (PK), `Name`, `Email`  
- **BorrowRecords** – `RecordID` (PK), `BookId` (FK), `MemberID` (FK), `BorrowDate`, `ReturnDate`  

The schema is available in **schema.sql**.

## ER Diagram
The ER diagram representing the relationships between the tables is in **ER Diagram.png**.

