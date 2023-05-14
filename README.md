# SQL modeling, structure and analysis in PostgreSQL.

For this project I have worked with basic concepts of data modeling, data engineering and data analysis.


## Data Modeling:

It was created an ERD - Entity Relationship Diagram of the company with all the tables and their relationships.

![Entity Relationship Diagram](https://github.com/Daniels2023/sql-challenge/assets/124798004/d563afa4-067d-4d90-8c7b-1327f4deeb01)


## Data Engineering:

All the csv's files was imported into their corresponding tables. I defined primary keys, foreing keys, and data types for each table.
Additionally, I had to format the data style to YYYY-MM-DD before importing it into PostgreSQL. For this, I used Pandas, as shown in the image below:

![image](https://github.com/Daniels2023/sql-challenge/assets/124798004/aa790e7b-9aa1-4cd9-8da7-db56e60b108b)


## Data Analysis:

It was analyzed the data and answered the following questions:

**1. List the employee number, last name, first name, sex, and salary of each employee.**

**2. List the first name, last name, and hire date for the employees who were hired in 1986.**

**3. List the manager of each department along with their department number, department name, employee number, last name, and first name.**

**4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.**

**5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.**

**6. List each employee in the Sales department, including their employee number, last name, and first name.**

**7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.**

**8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).**
