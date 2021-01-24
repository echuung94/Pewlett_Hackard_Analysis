# Pewlett_Hackard_Analysis

## Overview of the Analysis 

We were given the task of determining the number of retiring employees per title and identifying employees who are eligible to paritcipate in a mentorship program. Using the ERD that was created in the module as a reference, we created a Retirement Titles table that holds all the titles of current employees. We were to use the DISTINCT ON function so there were no titles reported multiple times, and the COUNT() function to create a final table that has the number of retirement-age employyes by most recent job title. After the two tables were created, we were then assigned to create a mentoship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965. 

## Results 

- The output shows that there are 133,776 employees who are born between January 1,1952 and December 31, 1955 currently employed and are entering retirement, which means that the company will soon be at a substantial loss.</br>
![retirement_count](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/retirement_count.png)</br>
![unique_titles](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/unique_titles.png)

- From the retiring employees table, we were to create another table with the different titles. There were 7 different titles with roughly 29,000 and 28,000 employees holding the title of a Senior Engineer and Senior Staff. The following showed roughly 14,000 Engineers, 12,000 Staff employees, around 4,500 Technique Leaders, and 1,700 Assistant Engineers. While there was a significant amount of Senior titles, there were only two employees, employed as a Manager.</br>
![retiring_titles](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/retiring_titles.png)

- While there is a total of 133,776 employees entering retirement, there are 1,549 employees who were born between January 1, 1965 and December 31, 1965 who are eligible to participate in a mentorship program. </br>
- There are no eligible employees retiring that can mentor the Management department. </br>
![mentor_count](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/mentor_count.png)

## ERD Schema 
The ERD Schema shown below was used to help build the queries for this assignment. 
![mentor_count](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/EmployeeDB.png)


## Summary 
How many roles will need to be filled as the "silver tsunami" begins to make an impact?</br>
- Based on the query outputs, there are over 90,000 roles that will need to be filled as the silver tsunami begins. </br>
![titles](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/titles.png)</br>

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?</br>
- Of the qualified, retirement-ready employees in the department, there are only 1,549 employees that are eligible to mentor the next generation of Pewlett Hackard employees. Although the number of eligible employees are high, I think it is best to know how many different titles are held by the employees. It would not be as helpful if there were 29,414 Senior Engineers and only 2 managers. I think it would be better if there was a good amount of eligible employees within each department. The HR deparment should work on why there is a small amount of Managers and work to bring in more Employees to take on the role as a manager at a big company like Pewlett Hackard.</br>
![rec1](https://github.com/echuung94/Pewlett_Hackard_Analysis/blob/main/Resources/rec1.png)
