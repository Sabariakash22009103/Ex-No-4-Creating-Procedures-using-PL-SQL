# Date:
# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
#### Creating Employee Table:
```sql
CREATE TABLE  emp3 (
    empid INT,
    empname VARCHAR(50),
    dept VARCHAR(50),
    salary NUMERIC
);
```
#### Creating a procedure:
```sql
CREATE PROCEDURE insert_emp3_data()
BEGIN
    INSERT INTO emp3 (empid, empname, dept, salary) VALUES (1, 'John', 'HR', 50000);
    INSERT INTO emp3 (empid, empname, dept, salary) VALUES (2, 'Joe', 'IT', 60000);
    INSERT INTO emp3 (empid, empname, dept, salary) VALUES (3, 'Bob', 'Finance', 55000);
    COMMIT;
END;
```
#### call the procedure:
```sql
call insert_emp_data();
```
### Output:
![image](https://github.com/Sabariakash22009103/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119390227/2086f1f4-e9ba-44ea-ab2e-e41aa18413d2)

### Result:
thus the creating a procedure using pl/sql is executed successfully.
