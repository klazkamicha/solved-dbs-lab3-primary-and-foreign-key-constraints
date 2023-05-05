Download Link: https://assignmentchef.com/product/solved-dbs-lab3-primary-and-foreign-key-constraints
<br>
<strong>EMPLOYEE(Fname,Minit,Lname,Ssn,Bdate,Address,Sex,Salary,Super_ssn,Dno) </strong>

<strong>DEPARTMENT(Dname,Dnumber,Mgr_ssn,Mgr_start_date) </strong>

<strong>DEPT_LOCATIONS( Dnumber, Dlocation) </strong>

<strong>PROJECT(Pname,Pnumber,Plocation,Dnum) </strong>

<strong>WORKS_ON(Essn,Pno,Hours) </strong>

<strong>DEPENDENT(Essn,Dependent_name.Sex,Bdate,Relationship) </strong>

<strong> </strong>

<strong>SSN is  social security number which is unique for each individual </strong>

Super_ssn is supervisor ssn number

<ol>

 <li>Assign constraints to the above schema (primary and foreign key constraints) and justify.</li>

 <li>Retrieve the names of all employees who do not have supervisors.</li>

 <li>select the Essn s of all employees who work the same (project, hours) combination on some project that employee ‘John Smith’ (whose Ssn = ‘123456789’)</li>

 <li>Retrieve the name of each employee who has a dependent with the same first name and is the same sex as the employee.</li>

 <li>Retrieve the names of employees who have no dependents.</li>

 <li>List the names of managers who have at least one dependent.</li>

 <li>Retrieve the Social Security numbers of all employees who work on project numbers 1, 2, or 3.</li>

 <li>Find the sum of the salaries of all employees, the maximum salary, the minimum salary, and the average salary.</li>

 <li>find the sum of the salaries of all employees of the ‘Research’ department, as well as the maximum salary, the minimum salary, and the average salary in this department.</li>

 <li>retrieve the names of all employees who have two or more dependents</li>

 <li>for each department, retrieve the department number, the number of employees in the department, and their average salary.</li>

 <li>For each project, retrieve the project number, the project name, and the number of employees who work on that project.</li>

 <li>For each project on which more than two employees work, retrieve the project number, the project name, and the number of employees who work on the project.</li>

 <li>For each project, retrieve the project number, the project name, and the number of employees from department 5 who work on the project.</li>

 <li>For each department that has more than five employees, retrieve the department number and the number of its employees who are making more than $40,000.</li>

 <li>For each department whose average employee salary is more than $30,000, retrieve the department name and the number of employees working for that department.</li>

 <li>Suppose that we want the number of male employees in each department making more than $30,000, rather than all employees Can we specify this query in SQL?</li>

 <li>Retrieve the names of all employees who work in the department that has the employee with the highest salary among all employees.</li>

 <li>Retrieve the names of all employees whose supervisor’s supervisor has ‘888665555’ for Ssn .</li>

 <li>Retrieve the names of employees who make at least $10,000 more than the employee who is paid the least in the company.</li>

 <li>Write a query to find the ssn of second highest salaried employee</li>

 <li>Retrieve top 3 Highest salaries records from Employee table</li>

 <li>Retrieve department wise max salary</li>

 <li>List dept no., Dept name for all the departments in which there are no employees in the department.</li>

 <li>Retrieve employee name as a concatenation of Fname , lname and minit</li>

 <li>Retrieve employee names whose first names is of 5  char  length</li>

 <li>Retrieve average salary of female employees</li>

 <li>Retrieve employees who works on all projects handled by department no 5</li>

 <li>Retrieve employees who works on all projects in chennai</li>

 <li>Retrieve employees who dont work on any project</li>

 <li>For each project list project name and total hours(by all employees) spent on that project</li>

 <li>Find the names of all employees who work on atleast one project located in chennai but whose department has no location in chennai</li>

 <li>Display names of all employees who work on some project controlled by dept no. 10</li>

 <li>Retrieve SSN , name of a supervisor who supervises highest no of employees</li>

 <li>Find SSN and first name of supervisor who supervises at least 2 projects in ascending order of number of employees under him</li>

 <li>Display the employees whose salary exceeds the department managers salary that employee(s) work for</li>

 <li>Display employee names who either work for research department or supervised by an employee from research department</li>

 <li>Display employee names who either works for research department or supervise and employee from research department</li>

 <li>Find all employees who were born during the 1950s</li>

 <li>Retrieve the names of all employees in department 5 who work more than 10 hours per week on the ProductX project.</li>

 <li>Count the number of distinct salary values in the database.</li>

 <li>Retrieve employees who works on atleast one project from each department</li>

 <li>Retrieve the names of employees who work on all the projects that “John Smith”’ works on.</li>

 <li>List project numbers for projects that involve an employee whose last name is ‘Smit’’, either as a worker or as a manager of the department that controls the project</li>

 <li>For every project located in “Chennai” , list the project number, the controlling department number, and the department manager’s last name, birth date, and address.</li>

</ol>








