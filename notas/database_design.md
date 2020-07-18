# Database design basic
From https://support.microsoft.com/en-us/office/database-design-basics-eb2159cf-1e30-401a-8084-bd4f9c9ca1f5?ui=en-us&rs=en-us&ad=us

## Database terms 
* Tables: stores information about something
* Record: row in the database. Has information about an item of the Database.
* Field: column in the database. Item of information that every row has.

## What is good database design?
* Divides information into subject-based tables
* Accuracy and integrity of information
* Can join the information between tables

## Design process steps
1. Determine de purpose of your database
2. Organize the information required
3. Divide into tables
4. Transform information into columns:
   1. Don't include calculated data: use reports for this
   2. Columns should contain the smallest information possible
5. Specify primary keys: identity of each row (unique and not null). Can use AutoNumber datatype
6. Setup table relationships
   1. One-to-many: PK of the one inside the many table (as a **foreign key**)
   2. Many-to-many: create a **junction table** with 2 PK
7. Normalization rules