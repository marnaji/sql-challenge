# sql-challenge
### Background
 Pewlett Hackard (a fictional company) asked my first task to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.
For this project, I designed the tables to hold the data from the CSV files, imported the CSV files into a SQL database, and then answered questions about the data. I performed data modeling, data engineering, and data analysis, respectively.

### Data Modeling 
CSV file has been inspected and I used  <a href="https://www.quickdatabasediagrams.com/" target="_blank"> QuickDBD </a> to create the sketch of an ERD ( Entity RElashionship Diagram).
Here is the image of the ERD:

<img src="/EmployeeSQL/QuickDBD-Employee Diagram.png" width="400" >

### Data Engineering
I created a table schema for each of the six CSV files. Then, I Imported each CSV file into its corresponding SQL table.

### Data Analysis
I answered all these 8 questions:
    1. List the employee number, last name, first name, sex, and salary of each employee.

    2. List the first name, last name, and hire date for the employees who were hired in 1986.

    3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

    4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

    5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

    6. List each employee in the Sales department, including their employee number, last name, and first name.

    7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

    8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

#### References
Data generated by <a href="https://mockaroo.com/" target="_blank"> Mockaroo, LLC, </a> (2022). Realistic Data Generator.
