# Database Design

A collection of database design coursework projects covering ER modelling, normalisation, relational schemas, and SQL.

These projects were completed during Semester 1 of my second year. The aim was to apply database design concepts by modelling different scenarios, creating relational schemas with keys and relationships, and using SQL to define tables, insert sample data, and query and update the databases.

## Assignment 1: Normalisation, ER diagrams, and database

Located in [`Normalisation-ER-diagrams-and-database/`](./Normalisation-ER-diagrams-and-database/).

- `DBD - Assignement 1.vpp` — Visual Paradigm project.
- `Database Design - Assignment 1 R00225669.pdf` — assignment document.
- `Task2.sql` — MySQL dump containing the car-hire database tables and sample data.
- `Task 3.txt` — sample queries and data changes for the car-hire database.

The SQL scripts refer to the database name `assignement1` Create that database before running the scripts.

## Assignment 2: Data modelling, design, and physical database

Located in [`Data-modelling-design-and-physical database/`](./Data-modelling-design-and-physical%20database/).

- `DD - Assignement 2.vpp` — Visual Paradigm project.
- `Database Design - Assignment 2 R00225669.pdf` — assignment document.
- `Create Tables.sql` — creates the horse-clinic schema in the `assignment2` database.
- `Insert to tables.sql` — inserts sample clinic, staff, owner, horse, consultation, and treatment data.

Create the `assignment2` database, then run `Create Tables.sql` followed by `Insert to tables.sql`.

## Running the SQL

The scripts are written for MySQL. Open them in MySQL Workbench or another MySQL client, create the database named in the script, and execute the relevant file. For Assignment 2, run the table-creation script before the insert script so that the required tables and foreign keys exist.

**Note:** `Task 3.txt` includes `UPDATE` and `DELETE` statements that modify data. Run it against a disposable or backed-up database if you want to preserve the original sample data.
