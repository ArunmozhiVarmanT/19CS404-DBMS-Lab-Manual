# Experiment 3: DML Commands

## NAME : ARUNMOZHI VARMAN T
## REG NO : 212223230022


## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
--
<img width="893" height="228" alt="image" src="https://github.com/user-attachments/assets/6e586657-af20-4435-b27b-9a2c704ea91e" />


```
UPDATE products
SET product_name = 'Grapefruit'
WHERE product_id = 4;

```

**Output:**

<img width="1262" height="272" alt="image" src="https://github.com/user-attachments/assets/216088ac-2d06-45f1-97b7-af815e675d62" />

**Question 2**
---
<img width="727" height="116" alt="image" src="https://github.com/user-attachments/assets/d6f48afc-e613-481d-ba0f-2c6793e9809c" />

```
UPDATE Customer
SET grade = 5
WHERE city = 'Chennai';

```

**Output:**

<img width="1241" height="506" alt="image" src="https://github.com/user-attachments/assets/54183330-4e06-4b9f-8722-53762873a352" />

**Question 3**
---
<img width="841" height="322" alt="image" src="https://github.com/user-attachments/assets/3e3640a7-ec3f-4cc2-971f-d709cb81afb4" />

```
UPDATE Products
SET quantity = quantity * 1.10;

```

**Output:**

<img width="1283" height="630" alt="image" src="https://github.com/user-attachments/assets/e42914db-ffcb-4cbb-a8de-6486d908cec5" />

**Question 4**
---
<img width="945" height="279" alt="image" src="https://github.com/user-attachments/assets/c6451114-f24e-42f3-97bb-dec2372e4378" />

```
UPDATE suppliers
SET supplier_name = 'A1 Suppliers'
WHERE supplier_id = 8;

```

**Output:**

<img width="1283" height="453" alt="image" src="https://github.com/user-attachments/assets/84c68d00-6d3f-4c29-b82e-fbc1dbaafa3b" />

**Question 5**
---
<img width="968" height="593" alt="image" src="https://github.com/user-attachments/assets/12e70ca1-b3bf-48b7-8a92-2a05bc7f43aa" />

```
UPDATE employees
SET email = 'Unavailable';

```

**Output:**

<img width="1248" height="463" alt="image" src="https://github.com/user-attachments/assets/f5dc325a-6d49-4f71-bc9b-0928e600270c" />

**Question 6**
---
<img width="778" height="534" alt="image" src="https://github.com/user-attachments/assets/030e5254-7fcc-43e3-8e1b-17d3bf5d81d5" />

```
DELETE FROM Doctors
WHERE last_name IS NULL;
```

**Output:**
<img width="1175" height="711" alt="image" src="https://github.com/user-attachments/assets/7f4c666a-0589-4d93-a216-2a7ff076190f" />


**Question 7**
---
<img width="876" height="169" alt="image" src="https://github.com/user-attachments/assets/c492b9e7-1c6c-4e8b-a882-7c9a5fe08642" />

```
DELETE FROM Doctors
WHERE specialization = 'Cardiology';
```

**Output:**

<img width="1179" height="410" alt="image" src="https://github.com/user-attachments/assets/e3e950f4-9ddf-4da7-9f8d-f98525c73f9b" />

**Question 8**
---
<img width="813" height="593" alt="image" src="https://github.com/user-attachments/assets/b149bdab-c381-497d-82b7-e35e285044b7" />

```
DELETE FROM Surgeries
WHERE surgery_id = 3
   OR surgeon_id = 4;
```

**Output:**

<img width="1345" height="922" alt="image" src="https://github.com/user-attachments/assets/b5f5de08-4245-45f1-9b64-b509174b6717" />

**Question 9**
---
<img width="1268" height="453" alt="image" src="https://github.com/user-attachments/assets/555ba60e-728d-423e-89fd-f57421c416b7" />

```
DELETE FROM Customer
WHERE grade = 3
  AND cust_name LIKE '%BBB%'
  AND payment_amt > 2000;
```

**Output:**

<img width="1239" height="502" alt="image" src="https://github.com/user-attachments/assets/030c0bf0-e33d-4e2f-93af-0e70f0bdcc39" />

**Question 10**
---
<img width="729" height="488" alt="image" src="https://github.com/user-attachments/assets/ef20c903-eb54-451f-8078-afd641f93678" />

```
DELETE FROM Doctors
WHERE specialization IS NULL;
```

**Output:**

<img width="1220" height="922" alt="image" src="https://github.com/user-attachments/assets/6d2b31a0-6843-45aa-a134-cbb477c1cbe5" />

## RESULT
Thus, the SQL queries to implement DML commands have been executed successfully.
