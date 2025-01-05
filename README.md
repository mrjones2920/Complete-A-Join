# Complete-A-Join
Introduction In this lab, you’ll use INNER JOIN, LEFT JOIN, and RIGHT JOIN in SQL to retrieve information from two different tables. You’ll use these different types of SQL joins to join data from separate machines, employees, and login attempts tables. You’ll be using the MariaDB shell to run SQL queries.

<h2>What you’ll do</h2>
You have multiple tasks in this lab:
  
   - Use an inner join to find information on employees and their machines
   - Use a left join and right join to find information on employees and their machines
   - Use an inner join to find information on employees and their login attempts

<h2>Scenario</h2>
In this scenario, you’ll investigate a recent security incident that compromised some machines.

You are responsible for getting the required information from the database for the investigation.

Here’s how you’ll do this task: First, you’ll use an inner join to identify which employees are using which machines. Second, you’ll use left and right joins to find machines that do not belong to any specific user and users who do not have any specific machine assigned to them. Finally, you’ll use an inner join to list all login attempts made by all employees.

<h2>Task 1. Match employees to their machines</h2>

First, you must identify which employees are using which machines. The data is located in the machines and employees tables.

You must use a SQL inner join to return the records you need based on a connecting column. In the scenario, both tables include the device_id column, which you’ll use to perform the join.

1.Run the following query to retrieve all records from the machines table:
![image](https://github.com/user-attachments/assets/f2fb3783-f312-441a-a2f7-9689c5c8157e)

2.Complete the query to perform an inner join between the machines and employees tables on the device_id column. Replace X and Y with this column name:
![image](https://github.com/user-attachments/assets/b23a37df-cfb0-4742-8f88-78bacb329a93)

<h2>Task 2. Return more data</h2>
You now must return the information on all machines and the employees who have machines. Next, you must do the reverse and retrieve the information of all employees and any machines that are assigned to them.

To achieve this, you’ll complete a left join and a right join on the employees and machines tables. The results will include all records from one or the other table. You must link these tables using the common device_id column.

1.Run the following SQL query to connect the machines and employees tables through a left join. You must replace the keyword X in the query:
![image](https://github.com/user-attachments/assets/6fd5a421-7356-4255-947f-81080ac08c42)

2.Run the following SQL query to connect the machines and employees tables through a right join. You must replace the keyword X in the query to solve the problem:
![image](https://github.com/user-attachments/assets/879fa2d1-5fcf-43d0-9b30-dbe9366e14a0)

<h2>Task 3. Retrieve login attempt data</h2>
To continue investigating the security incident, you must retrieve the information on all employees who have made login attempts. To achieve this, you’ll perform an inner join on the employees and log_in_attempts tables, linking them on the common username column.

- Run the following SQL query to perform an inner join on the employees and log_in_attempts tables. Replace X with the name of the right table. Then replace Y and Z with the name of the column that connects the two tables:

![image](https://github.com/user-attachments/assets/44fbd20e-fefe-4157-8ae3-0b013e1d8c0e)


<h2>Conclusion</h2>
Great work!

You have completed this activity and should be able to use joins to combine data from multiple tables in a database.

You now have practical experience in using

INNER JOIN,
LEFT JOIN, and
RIGHT JOIN.
Great work using SQL joins to obtain the precise data you need.
