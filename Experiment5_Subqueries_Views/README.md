# Experiment 5: Subqueries and Views

## AIM
To study and implement subqueries and views.

## THEORY

### Subqueries
A subquery is a query inside another SQL query and is embedded in:
- WHERE clause
- HAVING clause
- FROM clause

**Types:**
- **Single-row subquery**:
  Sub queries can also return more than one value. Such results should be made use along with the operators in and any.
- **Multiple-row subquery**:
  Here more than one subquery is used. These multiple sub queries are combined by means of ‘and’ & ‘or’ keywords.
- **Correlated subquery**:
  A subquery is evaluated once for the entire parent statement whereas a correlated Sub query is evaluated once per row processed by the parent statement.

**Example:**
```sql
SELECT * FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```
### Views
A view is a virtual table based on the result of an SQL SELECT query.
**Create View:**
```sql
CREATE VIEW view_name AS
SELECT column1, column2 FROM table_name WHERE condition;
```
**Drop View:**
```sql
DROP VIEW view_name;
```

**Question 1**

<img width="1088" height="710" alt="image" src="https://github.com/user-attachments/assets/5615f3a3-dd1d-412c-a8d0-03b163d314a5" />


**Output:**

<img width="1204" height="408" alt="image" src="https://github.com/user-attachments/assets/0384e62e-ea6b-4afe-9c7b-2594ba1d3edb" />


**Question 2**



<img width="1225" height="862" alt="image" src="https://github.com/user-attachments/assets/a3063760-1529-43a4-a41d-aa244eac6c0e" />


**Output:**


<img width="1248" height="434" alt="image" src="https://github.com/user-attachments/assets/bb573579-4ba0-4382-a968-09486299efae" />


**Question 3**

<img width="1193" height="789" alt="image" src="https://github.com/user-attachments/assets/60504a6b-e286-4b69-bd7c-180fd57079da" />

**Output:**

<img width="1045" height="398" alt="image" src="https://github.com/user-attachments/assets/8afdda29-2e77-464f-adf1-71d128aeb8bb" />


**Question 4**

<img width="1176" height="826" alt="image" src="https://github.com/user-attachments/assets/fe95b3e6-2b21-4c3c-8593-f6579ece23e2" />

**Output:**

<img width="725" height="509" alt="image" src="https://github.com/user-attachments/assets/d575bd1d-7482-4821-a6f1-1fc3c717b422" />


**Question 5**

<img width="1084" height="832" alt="image" src="https://github.com/user-attachments/assets/78c371dc-0bc3-4ef1-bbce-509ad24b8524" />


**Output:**

<img width="1110" height="518" alt="image" src="https://github.com/user-attachments/assets/9dce35c0-9f35-43af-b131-71b563f18067" />


**Question 6**

<img width="1371" height="910" alt="image" src="https://github.com/user-attachments/assets/505da5f2-5367-4536-b699-47f239df8e53" />


**Output:**


<img width="542" height="408" alt="image" src="https://github.com/user-attachments/assets/c348e1db-c44c-4f65-ba99-cc68a73219f8" />

**Question 7**

<img width="1270" height="734" alt="image" src="https://github.com/user-attachments/assets/46728185-99ad-49f5-8e3b-2846254e059d" />


**Output:**

<img width="1154" height="387" alt="image" src="https://github.com/user-attachments/assets/cce643eb-5a19-47e2-8b22-6fa2b3838350" />


**Question 8**

<img width="1151" height="783" alt="image" src="https://github.com/user-attachments/assets/200e397f-ac1f-47fe-ad4b-00e24e163a2f" />


**Output:**

<img width="1198" height="374" alt="image" src="https://github.com/user-attachments/assets/bf006f62-329a-4990-8262-0735a9c9bd6f" />

**Question 9**


<img width="1009" height="888" alt="image" src="https://github.com/user-attachments/assets/4c6309aa-26af-44f4-8d5c-a04cbab15987" />

**Output:**

<img width="1094" height="524" alt="image" src="https://github.com/user-attachments/assets/d4985e24-815c-4257-902a-8cf508986356" />

**Question 10**


<img width="1015" height="543" alt="image" src="https://github.com/user-attachments/assets/e573aab6-58e8-44a6-8a87-9500e060d7cf" />

**Output:**

<img width="869" height="386" alt="image" src="https://github.com/user-attachments/assets/ed4997d2-e81b-4817-aca9-a53ca12ab693" />



## RESULT
Thus, the SQL queries to implement subqueries and views have been executed successfully.
