## sql-challenge

# For the data modelling part, an ERD was created to differentiate between the tables and the primary and foreign keys.

# For the data engineering part, six tables were created, avoiding any null values and indicating which of them are part of a string, integer or a date.

# For the data analysis part, the answers to the questions are described as follows:

#Q1 - a full outer join between the employees and salaries table to match the employees' salaries.

#Q2 - indication of the hire date to be greater than the date in quotation marks via the SELECT, FROM and WHERE.

#Q3 - a full join from the department manager table to the departments table, as well as an inner join to the employees table to avoid null values.

#Q4 - a full join on both department employees and employees tables as well as towards the departments table.

#Q5 - the WHERE part of the SELECT, FROM and WHERE would have the first name = Hercules AND last name LIKE B% indicating any last name starting with the letter B.

#Q6 - a full join from department employees to employees and also departments, using the WHERE function to focus on the Sales department

#Q7 - a full join from department employees to employees, then to departments - Sales and Development are the ones to the WHERE function.

#Q8 - The COUNT function is used for the last name - indicating AS frequency tells us the frequency of count. GROUP BY is then used to group by the employees. Is is then ordered by a descending order using ORDER BY and DESC functions.
