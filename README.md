# Event-Database-SQL-Project
A relational database designed to manage event logistics, participants, and feedback using SQL
# Relational Database Design for Information Management

## Project Overview
This project was part of my Data Science for Business degree at BI Norwegian Business School. The goal was to design and implement a relational database to manage complex event logistics, ensuring data integrity and optimized reporting.

##  Tech Stack
- **Database:** SQLite
- **Modeling:** ER Diagram, Relational Schema
- **Language:** SQL (DDL, DML)

##  Key Features
- **ER Diagram:** Designed a multi-entity relationship model (Participants, Sessions, Roles).
- **Business Constraints:** Handled parallel sessions, dietary restrictions, and specific role permissions (Organizers vs. Speakers).
- **Integrity:** Implemented Primary Keys, Foreign Keys, and CHECK constraints.

##  How to use
You can find the full SQL scripts in the `scripts/` folder.
1. Run `schema.sql` to create the tables.
2. Run `insert_data.sql` to populate the sample database.
3. View live SQL demo here: https://www.db-fiddle.com/f/wqNfgRDhDQk7GG2WgybsTJ/0
