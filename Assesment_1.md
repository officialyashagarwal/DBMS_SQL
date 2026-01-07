# Oracle Live SQL Account Create Link

## Step 1: Website Open https://profile.oracle.com/myprofile/account/create-account.jspx


# 🧠 SQL ( Structure Query Language )  
## SQL commands are fundamental building blocks used to perform given operations on database.The operations include queries of data. creating a table, adding data to tables, dropping the table, modifying the table and set permission for users.
---
# 📖 Basic Rules for Writing SQL Command
## 1. Keywords are UPPERCASE ### Always write SQL keywords (like SELECT, INSERT, UPDATE, DELETE, CREATE) in uppercase.
## 2. End every command with a semicolon (;) ###  A semicolon tells SQL that the command is finished
## 3. Use single quotes for text values ### Strings/text must be inside 'single quotes'.
## 4. Table and column names are lowercase or snake_case ### Keep names simple, avoid spaces.
## Example: student_id, course_name.
## 5. Indent and format for readability ###  Write each clause on a new line.
``` Example:
SELECT id, name
FROM Students
WHERE age > 18;
```
## 7. Use comments for clarity ###  Add -- for single‑line comments.
```sql comment
-- This query shows all students
SELECT * FROM Students;
```

## Example You are relate with Python also 

| Python       | DBMS    |
| ------------ | ------- |
| list         | table   |
| dict keys    | columns |
| dict values  | rows    |
| print()      | SELECT  |
| if condition | WHERE   |

## SQL Commands are mainly categorized into five categories: 

![sql_commands](https://github.com/user-attachments/assets/eac7f7cb-f2b9-44fc-9c19-77062f634e51)



 # 1. DDL - Data Definition Language 
 ## It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database

 | Command	    | Description	Syntax |
 |------------ | -------------------|
 | CREATE	     | Create database or its objects (table, index, function, views, store procedure and triggers)	CREATE TABLE table_name (column1 data_type, column2 data_type, ...);
 | DROP	       | Delete objects from the database	DROP TABLE table_name;
 | ALTER	      | Alter the structure of the database	ALTER TABLE table_name ADD COLUMN column_name data_type;
 | TRUNCATE	   | Remove all records from a table, including all spaces allocated for the records are removed	TRUNCATE TABLE table_name;
 | COMMENT	    | Add comments to the data dictionary	COMMENT ON TABLE table_name IS 'comment_text';
 | RENAME	     | Rename an object existing in the database	RENAME TABLE old_table_name TO new_table_name;
 
---
# Create Table code
```Sql
CREATE TABLE employees (
    employee_id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    hire_date DATE
);
```
---
# Insert data in Table
```
-- insert sql code in two ways
INSERT INTO employees (employee_id, first_name, last_name, hire_date)
VALUES (1, 'John', 'Doe', TO_DATE('2026-01-07', 'YYYY-MM-DD'));
INSERT INTO employees (employee_id, first_name, last_name, hire_date)
VALUES (2, 'John', 'Doe', TO_DATE('07-Jun-2025'));

```
---
# Some Basic Question to Understand Sql Query's
✔ Checkpoint Questions
1. Write a query for print the employees table.
2. Write a query for insert a row in table.


``` Sql Questions
