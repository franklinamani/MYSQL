# Lab 5 — Database Normalization

**Student:** Franklin Safari   
**File:** `lab5.sql`

## Description
This lab demonstrates the normalization of a poorly structured **1NF** relation into a collection of well-structured **3NF** relations. The goal of the assignment is to design and implement a normalized relational database using **SQL DDL statements**, while enforcing data integrity through appropriate primary and foreign key constraints.

The database represents a publishing system that includes publishers, authors, books, authorship relationships, and book series volumes.

## Tables Created
- `Publisher`
- `Author`
- `Book`
- `Authorship`
- `Volume`

All tables are designed in **Third Normal Form (3NF)** to minimize redundancy and maintain consistency.

## Technologies Used
- MySQL
- SQL (DDL concepts)

## How to Execute
```bash
mysql --login-path=Lab5 Lab5 < lab5.sql
