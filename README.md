# Employee-Performance-Mapping---MYSQL
                                            #Synopsis
# Project Objective:
To build a robust SQL-based system that effectively maps and analyses employee performance data, enabling data-driven insights for informed decision-making and strategic HR planning.
# Problem Statement:
Many organizations struggle with manual and inefficient methods of tracking and analysing employee performance data. This can lead to suboptimal decision-making, difficulty in identifying high-performing employees, and challenges in recognizing and addressing performance gaps.
# Proposed Solution:
This project aims to develop a SQL-based solution that automates the process of collecting, storing, and analysing employee performance data. By leveraging the power of SQL, we will create a comprehensive database that captures key performance metrics
# Expected Benefits:
•	Improved Decision-Making: Data-driven insights to support strategic HR decisions
•	Enhanced Performance Management: Effective identification and recognition of top performers
•	Increased Employee Engagement: Transparent and fair performance evaluation processes
•	Optimized Resource Allocation: Efficient deployment of resources based on performance data
•	Reduced Turnover: Proactive measures to address performance issues and retain top talent
# Technical Approach:
•	Database Design: Create a well-structured SQL database to store employee performance data
•	SQL Queries: Develop complex SQL queries to extract, transform, and analyze data
By leveraging the power of SQL, this project will provide a valuable tool for HR teams to make informed decisions, improve employee performance, and ultimately drive organizational success.

# Output Screenshots
                                                             Output Screenshots
1.	Create a database named employee, then import data_science_team.csv proj_table.csv and emp_record_table.csv into the employee database from the given resources.
#   ![image](https://github.com/user-attachments/assets/b58d4ed2-75a6-4d28-bede-51e4674e7ec1)

2.Create an ER diagram for the given employee database.
#  ![image](https://github.com/user-attachments/assets/965a3c5f-c594-4a52-a7aa-93119e8b8dab)

3. Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, and DEPARTMENT from the employee record table, and make a list of employees and details of their department.
#  ![image](https://github.com/user-attachments/assets/4162a10a-74d6-4998-903c-6d085e99bf99)

 

4.Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, DEPARTMENT, and EMP_RATING if the EMP_RATING is: 
•	less than two
•	greater than four 
•	between two and four
# ![image](https://github.com/user-attachments/assets/31554a77-907b-4cc7-b3c2-170d7609b645)


 
5.Write a query to concatenate the FIRST_NAME and the LAST_NAME of employees in the Finance department from the employee table and then give the resultant column alias as NAME.
# ![image](https://github.com/user-attachments/assets/9f67042b-ba55-4379-aec4-4ddfddef0976)

 

6.Write a query to list only those employees who have someone reporting to them. Also, show the number of reporters (including the President).
# ![image](https://github.com/user-attachments/assets/eb6fbe06-760d-46ac-bbb1-15541cb188b5)

 

7.Write a query to list down all the employees from the healthcare and finance departments using union. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/487d3b35-da80-4678-ae6a-35d8f010bc63)

8.Write a query to list down employee details such as EMP_ID, FIRST_NAME, LAST_NAME, ROLE, DEPARTMENT, and EMP_RATING grouped by dept. Also include the respective employee rating along with the max emp rating for the department.
# ![image](https://github.com/user-attachments/assets/2d9780d6-ee8a-4f2e-aabf-75e4ee37cc5c)

9.Write a query to calculate the minimum and the maximum salary of the employees in each role. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/e5a07e15-61f2-4d30-aacc-8a51bd299840)

10.Write a query to assign ranks to each employee based on their experience. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/42d72011-a210-4947-bae5-acea7f60c4a8)

11.Write a query to create a view that displays employees in various countries whose salary is more than six thousand. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/37c50e7c-9c94-47c2-9d62-800f160a5d9f)

 
12. Write a nested query to find employees with experience of more than ten years. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/8d5e50e8-2cb5-435e-bc24-53f960ea44fa)

 
13.Write a query to create a stored procedure to retrieve the details of the employees whose experience is more than three years. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/cd58db63-fe84-44e8-a490-a017296e4c2c)

14.Write a query using stored functions in the project table to check whether the job profile assigned to each employee in the data science team matches the organization’s set standard.

The standard being:
For an employee with experience less than or equal to 2 years assign 'JUNIOR DATA SCIENTIST',
For an employee with the experience of 2 to 5 years assign 'ASSOCIATE DATA SCIENTIST',
For an employee with the experience of 5 to 10 years assign 'SENIOR DATA SCIENTIST',
For an employee with the experience of 10 to 12 years assign 'LEAD DATA SCIENTIST',
For an employee with the experience of 12 to 16 years assign 'MANAGER'.
# ![image](https://github.com/user-attachments/assets/697388a0-a38c-4dde-b735-18555ad753c5)
 

15.Create an index to improve the cost and performance of the query to find the employee whose FIRST_NAME is ‘Eric’ in the employee table after checking the execution plan.
# ![image](https://github.com/user-attachments/assets/b896b7b9-7f09-45f4-be77-62a8a208697f)
# ![image](https://github.com/user-attachments/assets/04ffa92b-fe4c-498b-a1ef-794bf3989b59)

16.Write a query to calculate the bonus for all the employees, based on their ratings and salaries (Use the formula: 5% of salary * employee rating).
# ![image](https://github.com/user-attachments/assets/8a7594cd-5cdd-4872-9007-dd78e0a24c35)

 
17.Write a query to calculate the average salary distribution based on the continent and country. Take data from the employee record table.
# ![image](https://github.com/user-attachments/assets/d8356a35-fada-49da-9dae-1d53b1e962aa)

 




