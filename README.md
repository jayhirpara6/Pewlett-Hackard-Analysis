# Pewlett-Hackard-Analysis


#### Overview

###### At Bobby's company, there is a "silver tsunami" approaching where a lot of his company's current employees are approaching retirement. The goal of this analysis is to see in who are the bulk of retirees in the company and also see who qualify to participate in a mentorship program to allow the continue to grow and eventually replace those that were Seniors and Managers.

#### Results

###### As expected, given that there is an age requirement to qualify for retirement, the majority of retiring employees had either Senior Engineer or Senior Staff in their titles. 

See screenshot below:

 

![](../main/Retiring_Population.png) ![](../main/mentorship_participants.png)

* Senior Engineers/Senior Staff make up 64% of the retiring population.
* Upon furhter investigation into the mentorship_eligiblity table
	* we find that there are a significant amount of Senior Engineers/Staff that are eligible to be participants
* 1,549 employees are eligible for the mentorship program
* There are 33,118 employees currently employed.


#### Summary

##### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
###### Based on the below code - 

##### Are there enough qualified-retirement-ready employees in the departments to mentor the next generation of PH Employees?
###### The below code breaks down the retirement population from retirement_info by department. 

![](../main/retire_dept.png) ![](../main/retire_dept_output.png)

###### We also have a breakdown of the mentorship participants by department by adjusting the code slightly

![](../main/mentor_dept.png) ![](../main/mentor_dept_output.png)

###### Based on that query looks like the mentorship program will have enough mentors based on the departments.