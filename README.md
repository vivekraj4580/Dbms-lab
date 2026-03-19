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
