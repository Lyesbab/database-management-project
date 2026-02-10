# Database Management Project (INFO3114)

## Overview
Academic group project focused on designing and implementing a relational database to optimize business operations.
Work includes data normalization, conceptual/logical/physical modeling (MCD/MLD/MPD), and MySQL implementation.

## Key Work Completed
- Data normalization into 7 tables: Clients, Employees, Suppliers, Products, Orders, Categories, Order_Details
- Data modeling: MCD + MLD generated with Looping
- Physical schema implementation in MySQL (tables with PK/FK constraints)
- Database objects:
  - View (sales / revenue per employee)
  - Trigger (automatic stock update after orders)
  - Stored procedure (product restocking)
- User & privileges management:
  - `admin` (full privileges)
  - `operateur` (read-only)

## Repository Structure
- `report/` : project report (PDF/DOCX)
- `diagrams/` : MCD/MLD files
- `data/` : CSV/Excel datasets used in the project
- `sql/` : SQL scripts (schema, views, triggers, procedures, users)

## Technologies
- MySQL
- SQL (DDL/DML)
- Data Modeling (MCD/MLD/MPD)
- phpMyAdmin / Looping

## Authors
Group 3 (INFO3114)
- Lyes Babou
- Henock Segoun
- Brice Tchefindjim
