# Data Warehouse - AirAsia Flight Ticket Booking System

This repository contains documentation for a data warehouse implementation for AirAsia's flight ticket booking system. The project includes both relational (IBM DB2) and NoSQL (MongoDB) database approaches as demonstrated in the assignment reports.

## Project Overview

This data warehouse tracks information related to AirAsia flight bookings including:
- Customer details
- Flight information
- Locations
- Time dimensions
- Company data
- Promotions
- Payment methods
- Sales transactions

## Repository Contents

This repository serves as documentation for the AirAsia Data Warehouse project. All implementation details, including SQL scripts and NoSQL commands, are contained in the assignment reports referenced below.

- `README.md` - This file, providing an overview of the project
- `documentation/` - Additional documentation files (if any)

## Database Implementations

The project encompasses two database implementations:

### Relational Database (IBM DB2)
- Star schema design
- Dimension and fact tables
- Stored procedures, triggers, and user-defined functions
- Complex analytical queries

### NoSQL Database (MongoDB)
- Document-based model
- Embedded documents for related data
- Advanced queries using MongoDB query language
- Aggregation pipelines

## Implementation Reference

> **Important Note:** This repository does not contain the actual SQL scripts or NoSQL commands. For the complete implementation details, please refer to the assignment reports:

- **Assignment 1** (Sections 4.0 - 7.4): Contains all relational database implementation details
  - Data Definition Language (DDL)
  - Data Manipulation Language (DML)
  - Stored Procedures
  - Triggers
  - User-Defined Functions
  - Complex Queries

- **Assignment 2** (Sections 3.0 - 8.2): Contains all NoSQL database implementation details
  - Collection creation
  - Document insertion
  - Complex queries with logical operations
  - Aggregation pipelines
  - Update and delete operations

## Setup Instructions

To implement this data warehouse, you will need to:

1. Refer to the assignment reports for all SQL scripts and NoSQL commands
2. Set up the appropriate database systems:
   - IBM DB2 for the relational implementation
   - MongoDB for the NoSQL implementation
3. Execute the scripts provided in the reports in the correct sequence

### IBM DB2 Setup Overview

1. Install IBM DB2
2. Create a new database named "airasia"
3. Extract and execute the DDL scripts from Assignment 1, Section 4.0
4. Extract and execute the DML scripts from Assignment 1, Section 5.0
5. Implement procedural SQL from Assignment 1, Section 6.0
6. Run complex queries from Assignment 1, Section 7.0

### MongoDB Setup Overview

1. Install MongoDB
2. Create a new database named "AirAsia"
3. Create collections as described in Assignment 2, Section 3.0
4. Insert documents as shown in Assignment 2, Section 4.0
5. Execute queries from Assignment 2, Sections 5.0 - 8.2

## Key Features

- Star schema design for relational database
- Document-based model for NoSQL database
- Stored procedures, triggers, and user-defined functions
- Complex analytical queries
- Data dictionary and storage size calculations

## Contributors

- Nur Fatin Nabilah Binti Md.Irzan
- Nur Alia Shazwani Binti Mohd Nazri
- Haizatul Nazirah Nizam Binti Hairunizam
- Wong Jin Yin

## License

This project is for educational purposes only.
