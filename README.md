# INTRODUCTION TO EXCEL
![Microsoft_Excel_2013-2019_](https://github.com/ARBICE11/TASK_123/assets/140498286/ac141da9-ec86-4c32-aec5-66e80bebb6ee)

#### QUESTION 1
In worksheet 1, create a table with 20 rows of information having the fields below:
- Employee ID
- Employee Full Name
- Department (Communications, Sales, I.T)
- Salary (between $5000 to $25000)
- Job type (Part-time, Freelance, Contract)
#### MY INITIATIVE
----
I computed the table as advised which comprises of 20 rows and 5 columns; each column contains Employee ID, Employee full name, Department, Salary Scale, and Job type respectively. Employee ID has a unique prefix "SLA" before three (3) unique ascending numbers that were peculiar to each employee.
![DATA SET](https://github.com/ARBICE11/TASK_123/assets/140498286/0101c4be-dc28-4965-a7d8-4ecf198b537d)
#### QUESTION 1
----
In worksheet 1, show only employees who are 'Freelancers' and highlight the ones whose salaries are above $10000.
#### MY INITIATIVE
-----
From the **Data** ribbon, I clicked on the **Filter** command which provided a **drop-down** menu that enabled me to filter the table as desired. Firstly, I used the drop-down menu to filter the **Job type** by unticking the rest and ticking the **_freelance_** only. I then proceeded to the **Home** ribbon and I clicked on the **Conditional Formating**. I then clicked on the **Highlight cell rules**, then I selected **Greater than** function which allowed me to input **$10000**; this retained employees whose earnings/remunerations were greater than $10000. 
![SOLUTION TO QUESTION 1](https://github.com/ARBICE11/TASK_123/assets/140498286/6ca60839-dc9a-4afd-8177-9343f956deee)
#### QUESTION 2
----
In worksheet 2, split the employees' full names into first names and last names. Check for duplicates and highlight, if any (do not delete).
#### MY INITIATIVE
----
I selected the cell containing the **Employee Fullname** in order to split it into **_first name_** and **_last name_**. I then selected **Data** and clicked on **Text to Columns**. From there, I selected **_Delimited_** and clicked on **_Next_**. I then clicked on **_space_**, then I selected **_next_** again and proceeded to select where I want to place the new columns which i have named _first name and _last name_ and I clicked on finish. I highlighted the _first name_ and the _lastname_ columns and i clicked on **conditional formatting** command, I then used the **highlight cell rules**, then selected **duplicate values**. However, nothing was highlighted because my data do not have duplicate values.
![SOLUTION TO QUESTION 2](https://github.com/ARBICE11/TASK_123/assets/140498286/5177bc0f-81fd-46e0-a6fd-6c622700970e)
P.S: I used the **CONCAT** command in the last column to recollect and practice what we were taught.
#### QUESTION 3
----
In worksheet 3, highlight employees whose names begin with the letter "E" (in yellow). Format the salary column such that the highest SALARY has green background and the lowest SALARY has a red background.
#### MY INITIATIVE
----
From the  **Data** ribbon, I clicked on the **Filter** command which provided a **drop-down** menu that enabled me to filter the table as desired. Firstly, I used the drop-down menu to filter the **Employees full name** by using the **_Text Filters_**. I clicked on **_Text Filters_**, then I selected **Begin with** command; this enabled me to input the letter "E" and clicked Ok. This Filtered out **_Efe Tobore_** and I highlighted it in **_Yellow_**.
In the light of the above, I formated the salary column by using the filter drop-down menu to select **sort from largest to smallest**, this showed the employees that got the **highest pay** and the **lowest pay**. i.e **$25000** and **$5000**, I then proceeded to highlight them in **green** and **red** respectively.
![SOLUTION TO QUESTION 3](https://github.com/ARBICE11/TASK_123/assets/140498286/97c1dcf9-e1f0-4cdb-a37f-9a806c0283f7)
#### TASK 2, TASK 3
----
Using the same Sales Data, determine the following:
- The total revenue and profit generated
- The average revenue and units sold for every order
- The total Discount given in $
- Total number of sales recorded
- The highest profit generated
- Create a column named 'Sales Range', return 'High Sales' if the Sales value is above average, otherwise, return 'Low Sales'.
- The average revenue generated from each sale of 'Paseo'
- The number of sales made in the Government and Midmarket segment
- The total revenue generated from the sales of 'Montana' in Canada
- What is the total profit made in December?
- ![SALES DATA SET](https://github.com/ARBICE11/TASK_123/assets/140498286/52f7b800-78fe-42d9-ad2e-3615cf4b8133)

 #### MY INITIATIVE
 ----
 For the total revenue generated in $; I used this fomular: =SUM(J2:J701
