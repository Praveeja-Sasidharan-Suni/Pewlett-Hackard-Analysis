# Pewlett-Hackard-Analysis


## Overview of the analysis:

The HR Department at Pewlett Hackard needed an analysis to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship 
program.Then, we will write a report that summarizes our analysis based on  number of staff, department, and title who are retiring. Because a significant portion of the company is
close to requirement, HR would like to set up a mentorship program based on years of experience. 

1. ***Deliverable 1***: The Number of Retiring Employees by Title
2. ***Deliverable 2***: The Employees Eligible for the Mentorship Program
3. ***Deliverable 3***: A written report on the employee database analysis 

## Software
PostgreSQL, pgAdmin

## Results: 
#### Retiring by Title Table: 


* Out Of the 300,024 employees within the company,90,398 employees are eligible for retirement.
* The resuts from the analysis show that 29,914 Senior Engineers and 28,254 Senior Staff will be eligible to retire.  
   A large percent are senior level and when they depart a lot of company horse power will be lost.
* The department with the most retirees is Development (25%) followed by Production (22%)

Here is the unique_titles table:

![unique_titles.PNG](https://github.com/Praveeja-Sasidharan-Suni/Pewlett-Hackard-Analysis/blob/main/Images/unique_titles.PNG?raw=true)

Here is the retiring_titles table:

![retiring_titles.PNG](https://github.com/Praveeja-Sasidharan-Suni/Pewlett-Hackard-Analysis/blob/main/Images/retiring_titles.PNG?raw=true)

#### Mentorship_eligibilty Table:

*A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
* There are 1,940 employees elibible for the mentorship program


![mentorship_eligibility](https://github.com/Praveeja-Sasidharan-Suni/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility.PNG?raw=true)


## Summary: 

Based on the analysis Pewlett Hackard is facing over 90,000 vacant positions of the 300,024 employees company wide. Pewlett hackard will face a lose of qualified trained employees
 because of the low number of employees who are eligible for mentorship to train replacements.

Additional age based queries can be ran to determine the oldest and youngest departments and prioritize mentorship with the oldest departments. this could minimize the turnover impact.
