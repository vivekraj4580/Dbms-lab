# Experiment No: 2  
## Title: Retrieving Data from Employee Table  

## Aim  
To perform various SQL SELECT queries on the Employee table for retrieving specific data.

---

## Queries / Tasks  

### 1. List all distinct job in Employee  

```sql
SELECT DISTINCT JOB 
FROM Employee;
```

### 2. List all information about employee in Department Number 30

```sql
SELECT * 
FROM Employee 
WHERE DeptNo = 30;
```

### 4. Find all information about all the managers as well as the clerks in department 30

```sql
SELECT * 
FROM Employee 
WHERE DeptNo = 30 
AND (JOB = 'MANAGER' OR JOB = 'CLERK');
```

### 5. List the Employee name, Employee numbers and department of all clerks

```sql
SELECT ENAME, EMPNO, DeptNo 
FROM Employee 
WHERE JOB = 'CLERK';
```

### 6. Find all managers not in department 30

```sql
SELECT * 
FROM Employee 
WHERE JOB = 'MANAGER' 
AND DeptNo <> 30;
```

### 7. List information about all Employees in department 10 who are not manager or clerks

```sql
SELECT * 
FROM Employee 
WHERE DeptNo = 10 
AND JOB NOT IN ('MANAGER', 'CLERK');
```

### 8. Find Employees and jobs earning between 1200 and 1400

```sql
SELECT ENAME, JOB 
FROM Employee 
WHERE SAL BETWEEN 1200 AND 1400;
```

### 9. List Name and Department Number of employee who are clerks, analyst or salesman

```sql
SELECT ENAME, DeptNo 
FROM Employee 
WHERE JOB IN ('CLERK', 'ANALYST', 'SALESMAN');
```

### 10. List Name and Department Number of employee whose names began with M

```sql
SELECT ENAME, DeptNo 
FROM Employee 
WHERE ENAME LIKE 'M%';
