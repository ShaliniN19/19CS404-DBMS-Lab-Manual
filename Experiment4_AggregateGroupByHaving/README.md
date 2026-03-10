# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**

<img width="1022" height="668" alt="image" src="https://github.com/user-attachments/assets/e65ee498-5b01-4e38-977b-77f5d35d35c5" />

**Output:**

<img width="714" height="487" alt="image" src="https://github.com/user-attachments/assets/e320b415-3db9-4112-ad5c-5465ac5dca77" />

**Question 2**

<img width="805" height="507" alt="image" src="https://github.com/user-attachments/assets/06268810-0f53-471e-aa55-0b042fe958a3" />


**Output:**

<img width="847" height="255" alt="image" src="https://github.com/user-attachments/assets/c92b1e7e-8553-49fc-b03a-803ce2482534" />


**Question 3**

<img width="822" height="586" alt="image" src="https://github.com/user-attachments/assets/f4dc9f4d-a000-4938-be2f-3c4cf81ec3d1" />

**Output:**

<img width="703" height="225" alt="image" src="https://github.com/user-attachments/assets/308ef3a2-dbe7-40ac-b9a5-2417145b50cc" />

**Question 4**

<img width="850" height="502" alt="image" src="https://github.com/user-attachments/assets/b0c492f6-c404-44d3-ade7-9cfddf59db20" />


**Output:**

<img width="736" height="293" alt="image" src="https://github.com/user-attachments/assets/3cc17f07-2835-4264-b1b0-fc60d4518f78" />


**Question 5**

<img width="1118" height="518" alt="image" src="https://github.com/user-attachments/assets/d698829e-e902-4277-958b-575a361d92d2" />


**Output:**

<img width="774" height="362" alt="image" src="https://github.com/user-attachments/assets/c3852436-b07c-4552-b229-ec403eb94e1f" />

**Question 6**

<img width="799" height="578" alt="image" src="https://github.com/user-attachments/assets/aaea093b-dc79-4f56-ab56-b6c970bd1e2e" />


**Output:**

<img width="620" height="295" alt="image" src="https://github.com/user-attachments/assets/a039cd90-6dd9-4c7c-8cd5-4bd11b3def78" />

**Question 7**

<img width="1091" height="537" alt="image" src="https://github.com/user-attachments/assets/b84f649f-c762-47f0-b9f2-235bcdbb29e7" />

**Output:**

<img width="745" height="379" alt="image" src="https://github.com/user-attachments/assets/c3021216-4443-45fe-a930-61b937842ee3" />


**Question 8**

<img width="1211" height="547" alt="image" src="https://github.com/user-attachments/assets/8d17a866-fe02-4a06-8ff4-a496a16a6daf" />


**Output:**

<img width="886" height="308" alt="image" src="https://github.com/user-attachments/assets/9d4f639a-f2b2-446e-b3b6-d016b5902e1a" />

**Question 9**

<img width="814" height="607" alt="image" src="https://github.com/user-attachments/assets/539680dc-f296-459a-8f6b-b15fa781fa14" />


**Output:**

<img width="842" height="328" alt="image" src="https://github.com/user-attachments/assets/491efb7a-64d2-42d6-917e-cf2998b15cb5" />


**Question 10**

<img width="938" height="541" alt="image" src="https://github.com/user-attachments/assets/b9753e11-1349-4ef8-b7f7-43b325a764f2" />

**Output:**

<img width="902" height="369" alt="image" src="https://github.com/user-attachments/assets/511d7288-406b-4de3-9c46-db307c41a7d3" />



## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
