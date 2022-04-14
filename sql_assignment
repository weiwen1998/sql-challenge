
-- Data Analysis Question 1
SELECT employees.emp_no, employees.last_name, employees.first_name, employees.sex, salaries.salary
FROM employees
FULL JOIN salaries ON employees.emp_no=salaries.emp_no

-- Data Analysis Question 2
SELECT employees.first_name, employees.last_name, employees.hire_date
FROM employees
WHERE 
	employees.hire_date > '1986-12-31'

-- Data Analysis Question 3
SELECT departments.dept_no, departments.dept_name, dept_manager.emp_no, employees.first_name, employees.last_name
FROM departments
FULL JOIN dept_manager ON departments.dept_no = dept_manager.dept_no
INNER JOIN employees ON dept_manager.emp_no=employees.emp_no

--Data Analysis Question 4
SELECT employees.emp_no, employees.first_name, employees.last_name, departments.dept_name
FROM employees
FULL JOIN dept_emp ON employees.emp_no=dept_emp.emp_no
FULL JOIN departments ON dept_emp.dept_no=departments.dept_no

--Data Analysis Question 5
SELECT employees.first_name, employees.last_name, employees.sex
FROM employees
WHERE employees.first_name='Hercules' AND employees.last_name LIKE 'B%'

--Data Analysis Question 6
SELECT employees.emp_no, employees.first_name, employees.last_name, departments.dept_name
FROM employees
FULL JOIN dept_emp ON employees.emp_no=dept_emp.emp_no
FULL JOIN departments ON dept_emp.dept_no=departments.dept_no
WHERE dept_name='Sales'

--Data Analysis Question 7
SELECT employees.emp_no, employees.first_name, employees.last_name, departments.dept_name
FROM employees
FULL JOIN dept_emp ON employees.emp_no=dept_emp.emp_no
FULL JOIN departments ON dept_emp.dept_no=departments.dept_no
WHERE dept_name='Sales' OR dept_name='Development'

--Data Analysis Question 8
SELECT last_name, COUNT(last_name)AS Frequency
FROM employees
GROUP BY last_name
ORDER BY
COUNT(last_name) DESC