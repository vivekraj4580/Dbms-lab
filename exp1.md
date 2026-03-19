# Experiment No: 1  
## Title: Table Creation and Basic SQL Operations  

## Aim  
To create tables, insert values and perform basic SQL operations like DELETE, UPDATE, ALTER, and DROP.

---

## Table Structure  

### EMPLOYEE Table  

| Column Name | Data Type | Size | Attributes |
|-------------|-----------|------|------------|
| EMPNO | NUMBER | 4 | Primary Key |
| ENAME | VARCHAR2 | 20 | Not Null |
| JOB | VARCHAR2 | 20 |  |
| MGR | NUMBER | 4 |  |
| HIREDATE | DATE |  |  |
| SAL | NUMBER | 10 |  |
| COMM | NUMBER | 7 |  |
| DEPTNO | NUMBER | 2 | Foreign Key |

### DEPARTMENT Table  

| Column Name | Data Type | Size | Attributes |
|-------------|-----------|------|------------|
| DEPTNO | NUMBER | 2 | Primary Key |
| DNAME | VARCHAR2 | 15 | Not Null |

---

## Queries / Tasks  

### 1. Create Employee_master table with data using Employee table  

```sql
CREATE TABLE Employee_master AS
SELECT * FROM Employee;
```

### 2. Delete all records from Employee_master whose DeptNo is 10

```sql
DELETE FROM Employee_master
WHERE DeptNo = 10;
```

### 3. Update 10% increase in salary of DEPTNO 20

```sql
UPDATE Employee_master
SET SAL = SAL + (SAL * 0.10)
WHERE DeptNo = 20;
