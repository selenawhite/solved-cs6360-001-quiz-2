Download Link: https://assignmentchef.com/product/solved-cs6360-001-quiz-2
<br>
<strong>Database Design</strong>










Use COMPANY database schema and specify following queries in <u>relational algebra</u><em>.</em>




<ol>

 <li>Retrieve the names of all employees in department 5 who work more than 10 hours per week on the ProductX project.</li>

</ol>




<ol start="2">

 <li>List the names of all employees who have a dependent with the same first name as themselves.</li>

</ol>




<ol start="3">

 <li>Find the names of all employees who are directly supervised by ‘Franklin Wong’.</li>

</ol>




<ol start="4">

 <li>For each project, list the project name and the total hours per week (by all employees) spent on that project.</li>

</ol>




<ol start="5">

 <li>Retrieve the names of all employees who work on every project.</li>

</ol>




<ol start="6">

 <li>Retrieve the names of all employees who do not work on any project.</li>

</ol>




<ol start="7">

 <li>For each department, retrieve the department name and the average salary of all employees working in that department.</li>

</ol>




<ol start="8">

 <li>Retrieve the average salary of all female employees.</li>

</ol>




<ol start="9">

 <li>Find the names and addresses of all employees who work on at least one project located in Houston but whose department has no location in Houston.</li>

</ol>




<ol start="10">

 <li>List the last names of all department managers who have no dependents.</li>

</ol>







***

COMPANY Database Schema




Employee (FName, LName, SSN, BDate, Address, Gender, Salary, SuperSSN, DNo)




Department (DName, DNo, MgrSSN, MgrStartDate)




Project(PName, PNo, PLocation, DNo)




Works_On (SSN, PNo, Hours)




Dept_Location (Dno, DLocation)




Dependent (Essn, Dependent_name, Gender, Bdate, Relationship)