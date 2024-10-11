# Softwware Engineer -- Walmart Simulation

## Overview

This repository contains a project for the Walmart Shipping Department that focuses on difficult technical projects for a variety of teams at Walmart.

## Tasks Completed

### Task 1: Heap Data Structure Development
- Retrieved the necessary data from the Walmart Shipping Department's provided repository.
- Developed a novel version of a heap data structure in Java for Walmart’s shipping department, showcasing strong problem-solving and algorithmic skills.

### Task 2 and 3: UML and ERD Design
- Designed a UML class diagram for a data processor, considering different operating modes and database connections.
- Created an entity relationship diagram to design a new database accounting for all requirements provided by Walmart’s pet department.

### Task 4: Populated the Database
Completed the task of inserting all of the data contained in the provided spreadsheets into the SQLite database. I wrote a Python script that:

- Reads each row from the spreadsheets.
- Extracts the relevant data.
- Munges it into a format that fits the database schema.
- Inserts the data into the database.

Spreadsheet 0 is self-contained and can simply be inserted into the database, but spreadsheets 1 and 2 are dependent on one another. Spreadsheet 1 contains a single product per row; I combined each row based on its shipping identifier, determined the quantity of goods in the shipment, and added a new row to the database for each product in the shipment. The origin and destination for each shipment in spreadsheet 1 are contained in spreadsheet 2. All the given data is valid — product names are always spelled the same way, and quantities are positive.
