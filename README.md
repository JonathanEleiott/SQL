# SQL & Database Basics

## Types of Databases

- Relational
  - Use tables made up of columns and rows
    - row = record (actual data)
    - column = field
    - Column Types
      - INTEGER - whole numbers
      - FLOAT - numbers with decimals
      - CHAR(#) - string with an exact character count
      - VARCHAR(#) - string up to the # of characters
      - DATE - date
      - BOOLEAN - boolean (true or false) (1 or 0)
      - TEXT - large amounts of text
      - NULL - null
    - Primary Keys unique identifier for each record (key in React, id)
      - cannot be NULL
      - a table can only have one
    - Foreign Keys
      - link two tables
      - reference the primary key of another table
    - Relationships
      - one-to-one
        - state - capitol
        - dragon - rider
      - one-to-many or many-to-one
        - book -< authors
        - archaeology site -< artifacts
        - owners -< pets
        - companies -< employees
        - teachers -< students
      - many-to-many
        - projects >-< devs
        - teachers >-< students
        - doctors >-< patients
    - Join/Junction Table
      - many-to-many relationships


- NoSQL (not only SQL)
  - everything else

- PostgreSQL (database software)
  - relational database

## SQL (Structured Query Language)

- language of the database
- SQL Queries - MUST END IN SEMICOLON
- SELECT * FROM table_name - select which table to start retrieving records from
  - will give us a new table with the information we ask for
- WHERE - filters out the records we don't want
- JOIN ON - combine data from multiple tables
  
- Rows
  - INSERT INTO table_name (column1, column2) VALUES (value1, value2) - adds a new record (row)
    - if you don't want to put in a value, don't name the column
  - UPDATE - modify an existing record
  - DELETE - remove a record
- Tables
  - CREATE - adds a new table
  - ALTER - modify existing table
  - DROP - delete a table
