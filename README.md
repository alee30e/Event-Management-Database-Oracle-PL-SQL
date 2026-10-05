# Event-Management-Database-Oracle-PL-SQL
An Oracle database project exploring SQL, PL/SQL, database design, triggers, cursors, collections, and stored programs.

# Event Management Database

A relational database project built with **Oracle Database and PL/SQL**, focused on learning and applying database design, SQL, and procedural database programming.

## About

This project explores how a relational database can be designed and implemented for an event management system.

It covers the full process, from designing the database structure and relationships to implementing more advanced SQL and PL/SQL functionality.

The system manages events, users, tickets, artists, schedules, locations, invoices, sponsorships, and reviews.

## What I Learned

Through this project, I worked with:

- Relational database design and normalization
- Entity-Relationship modeling
- SQL queries and joins
- Constraints and data integrity
- PL/SQL procedures and functions
- Explicit and parameterized cursors
- PL/SQL collections
- Exception handling
- LMD and LDD triggers
- Compound triggers
- Packages
- Complex PL/SQL data types

## Database Structure

The database includes entities such as:

- Users
- Clients and Organizers
- Cities and Locations
- Events
- Artists and Schedules
- Ticket Categories and Ticket Types
- Tickets and Invoices
- Sponsorships
- Reviews

The database was designed in **Third Normal Form (3NF)** to reduce redundancy and maintain data consistency.

## PL/SQL

The project includes several PL/SQL components used to process and validate data directly inside the database.

### Collections

All three main PL/SQL collection types are explored:

- Nested Tables
- Associative Arrays
- VARRAYs

They are used for organizing and processing data such as events, users, ticket categories, and ticket sales.

### Cursors

The project uses:

- Explicit cursors
- Parameterized cursors
- Cursors that depend on other cursors

These helped me understand how larger query results can be processed programmatically in PL/SQL.

### Exception Handling

Custom and predefined exceptions are used to validate operations and handle invalid situations according to the application's business rules.

### Triggers

Different types of triggers are implemented, including:

- Statement-level LMD triggers
- Row-level LMD triggers
- Compound triggers
- LDD triggers

These are used to automatically validate operations, maintain consistency, and react to database changes.

### Packages

A PL/SQL package groups related procedures, functions, and complex data types into a reusable component.

## Technologies

- Oracle Database 19c
- SQL
- PL/SQL
- Oracle SQL Developer
