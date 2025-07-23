
# Oracle SQL Banking Project

This project represents a complete relational database system for a fictional banking application, implemented using Oracle SQL. It was developed as part of a university database course and includes schema creation, data manipulation, queries, and advanced SQL features.

## Features

- **Database schema** with 5 main entities: `ANGAJAT`, `FUNCTIE`, `CLIENT`, `CONTRACT`, and `CARD`
- **Primary and foreign key constraints** to ensure referential integrity
- **Data insertion**, **updates**, and **deletions**
- **Recovery commands** using `FLASHBACK`
- **Complex queries** including:
  - Aggregations and groupings
  - Hierarchical queries
  - Subqueries and joins
  - Case statements
  - Date and string functions
- **Objects created**:
  - Views (`CREATE VIEW`)
  - Indexes (`CREATE INDEX`)
  - Synonyms (`CREATE SYNONYM`)

## Tables Overview

- **ANGAJAT**: Stores employee information such as name, contact, function, and hiring date
- **FUNCTIE**: Stores job positions and related salaries and bonuses
- **CLIENT**: Stores customer details and the responsible employee
- **CONTRACT**: Represents credit or debit contracts linked to a client
- **CARD**: Represents the financial card associated with a client

## Example Queries

- List clients with the number of contracts they hold
- Show employees hired in specific years
- Classify salaries into ranges using CASE
- Retrieve hierarchical structure of employee-customer responsibility
- Identify major clients using CNP substring patterns

## Sample Use Cases

- Adjust interest rates for contracts handled by a specific employee
- Identify clients with unknown phone numbers
- Calculate age eligibility from CNP
- Perform integrity validation across card and contract holders

## Requirements

- Oracle Database
- SQL*Plus or any Oracle-compatible SQL IDE (e.g., Oracle SQL Developer)

## How to Use

1. Run the schema creation statements to define tables
2. Insert sample data as shown
3. Execute queries to interact with and test the dataset
4. Modify or extend queries based on specific business logic

---

**Note:** This project simulates a real-world banking scenario and demonstrates proficiency in SQL querying, relational modeling, and Oracle-specific syntax.
