# Pewlett Hackard Analysis

## Pewlett Hackard Analysis Overview
* Help Pewlett Hackard prepare for the future “silver tsunami” as many current employees reach retirement age. 
* Upgrade large data files from CSV format into a structured SQL database.
* Determine the number of upcoming vacancies and positions to be filled.
* Determine employee eligibility for retirement packages and a mentorship program.

## Pewlett Hackard Analysis Resources

* Data Sources: departments.csv, employees.csv, dept_emp.csv, dept_manager.csv, titles.csv, salaries.csv
* Software: PostgreSQL 11.0, pgAdmin 4 6.1

## Pewlett Hackard Analysis Results
Analysis of the employee database to create the requested tables produced the following insights: 
* Deliverable 1: The Number of Retiring Employees by Title
   - More than 90,000 employees, or nearly 30% of the total current workforce will be imminently eligible for retirement packages.
   - 93% are either Engineers or Staff.
   - 64% are Senior in title.
 
* Deliverable 2: The Employees Eligible for the Mentorship Program
   - The employee mentorship program eligibility screen produced only 1,549 candidates.
   - That would require each candidate to mentor approximately 10 next generation employees each if all upcoming vacancies were to be filled.

## Pewlett Hackard Analysis Summary
High-level responses to the following questions and two additional queries or tables that may provide more insight into the upcoming "silver tsunami":

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
   - More than 90,000 employees, or nearly 30% of the total current workforce will be imminently eligible for retirement packages. 
   - 93% are either Engineers or Staff, and 64% are Senior in title.
   - A table summarizing potential salary cost savings by department of prospective retiring employees would provide additional insight regarding future departmental hiring budgets.

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
   - The initial employee mentorship program eligibility screen only produced 1,549 candidates, which would require mentoring approximately 10 next generation employees each if all upcoming vacancies were to be filled.
   - A table expanding the mentorship program eligibility requirements would provide further insight regarding the number of additional retirement-ready employees eligible to participate and become mentors.  
   - A table grouping the mentorship program eligible employees by department would provide added insight to help better match mentors and mentees by department.
