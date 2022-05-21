# Pewlett-Hackard-Analysis
## Overview of the Project
### Pewlett-Hackard (PH) needs to determine the number of retiring employees per title. Because the number of eligible employees is so great, PH also needs to identify employees who would be able to provide mentoring to the horde of new employees. pgAdmin for PostgreSQL coding was chosen as the tool to analyze the PH employee database and create the tables pertinent to the information requested.
## Results
### - Retiring titles with the highest number of retiring employees are the Senior Engineers and the Senior Staff. The breakdown by title can be seen in the table below.

Count of retiring employees by job title

![image](https://user-images.githubusercontent.com/102757676/169668850-76f4418a-2e7f-42aa-9287-978d185ecf5f.png)

### - It is notable that there are only 2 managers retiring. This likely means that each department will not suffer much of a hit in management, so there will be seasoned managers available to organize and oversee the training plans and work load of the new employees.
### - There are a total of 1549 eligible mentors across a variety of titles left to mentor the next wave of employees.  
### - From a small portion of the mentorship eligible employees, it is clear that these individuals have been with the company for nearly their entire careers. All the eligible employees were born in 1965, and their start dates are between about 1987 and 1999 meaning they started at PH at ages 22-34. This indicates that the eligible mentors are sufficiently seasoned not only at PH but also in the workforce in general. A snippet of the mentorship data table is shown below.

Eligible Mentors and Titles

![image](https://user-images.githubusercontent.com/102757676/169669292-892d3c5b-07f4-40e2-9988-35caada9c664.png)


## Summary
### A total of 72,461 employees are retiring from Pewlett-Hackard. The majority of roles to be filled are the Senior Engineers and the Senior Staff.
### Since there are only 1549 eligible mentors, based on the parameter that the employee was born in 1965, there are no where near enough mentors for the next generation of PH employees.

### An additional query that may provide more insight to prepare for the "silver tsunami" would be one that not only pulls the titles and counts of all retirement-eligible employees, but the impact to the departments. Specifically, Staff, Senior Staff, and Technique leader could be from any number of departments. Once the counts of retiring employees are uncovered for each department, another useful query would be one that shows how many employees from those departments under those titles are left to mentor the incoming new hires. It would be helpful to understand the specific mentorship needs for those departments and job titles losing many of their employees. 

### Furthermore, a query that provides the data for the number of current employees in Staff and Engineering roles would be beneficial to see if there are enough current employees to fill the Senior Engineer and Senior Staff roles left by the retirees.
