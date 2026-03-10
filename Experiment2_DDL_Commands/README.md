# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**
<img width="1144" height="582" alt="image" src="https://github.com/user-attachments/assets/d7c4630b-1f35-4fb6-ba66-6e5eab5779ae" />


**Output:**
<img width="1140" height="188" alt="image" src="https://github.com/user-attachments/assets/d99e570c-d8bf-48f8-9a8f-af6468157974" />

**Question 2**
<img width="1148" height="649" alt="image" src="https://github.com/user-attachments/assets/89262eea-3f73-4945-a4a6-a3079eec62f3" />


**Output:**
<img width="1137" height="356" alt="image" src="https://github.com/user-attachments/assets/051692d6-5532-4c74-a7d0-44c8a7e1e34f" />

**Question 3**
<img width="1153" height="606" alt="image" src="https://github.com/user-attachments/assets/a83923c4-92c1-4a28-b555-722381b1df73" />


**Output:**
<img width="1141" height="403" alt="image" src="https://github.com/user-attachments/assets/fdaca61c-4143-4762-976b-140dcc73f338" />


**Question 4**
<img width="1170" height="537" alt="image" src="https://github.com/user-attachments/assets/2324a700-b6be-4ce0-b9f3-6dea5d0621b8" />


**Output:**
<img width="1102" height="358" alt="image" src="https://github.com/user-attachments/assets/827ecb46-7a7a-4685-8044-dd6b982d8c42" />

**Question 5**
<img width="1177" height="508" alt="image" src="https://github.com/user-attachments/assets/991bd672-8495-442c-81e4-3b029a7beceb" />


**Output:**
<img width="1202" height="415" alt="image" src="https://github.com/user-attachments/assets/1274afdd-737e-4284-b00d-fb87efedbe80" />

**Question 6**
<img width="1151" height="566" alt="image" src="https://github.com/user-attachments/assets/48d48a1b-b965-4dea-a308-e2b1bb536032" />

**Output:**
<img width="1155" height="335" alt="image" src="https://github.com/user-attachments/assets/5bb6cde4-53bb-4199-b420-c096a464e631" />


**Question 7**
<img width="1139" height="762" alt="image" src="https://github.com/user-attachments/assets/9bb656b7-f2d5-45ee-b44e-709275929b48" />


**Output:**
<img width="1137" height="392" alt="image" src="https://github.com/user-attachments/assets/1d2d36a7-074c-47ee-a436-b6135251e130" />


**Question 8**

<img width="1159" height="466" alt="image" src="https://github.com/user-attachments/assets/ba9e3446-cd8a-46f6-91f8-3950937476cc" />

**Output:**
<img width="1218" height="323" alt="image" src="https://github.com/user-attachments/assets/0dc29115-da07-4bd6-9fb7-bc353ac2674b" />

**Question 9**
<img width="1249" height="446" alt="image" src="https://github.com/user-attachments/assets/7e189469-ea21-467c-bc60-f09290afc12a" />

**Output:**
<img width="1164" height="315" alt="image" src="https://github.com/user-attachments/assets/2d17d946-f255-40ba-b636-48dc67c7d6e2" />

**Question 10**
<img width="1176" height="710" alt="image" src="https://github.com/user-attachments/assets/f6b69f98-c81a-4ff9-b8a3-6d3c07cb8bfc" />

**Output:**
<img width="1186" height="455" alt="image" src="https://github.com/user-attachments/assets/b1f32354-fecd-4f16-a5c4-adb90b18d6e2" />

## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
