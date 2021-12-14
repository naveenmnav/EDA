## HR Attrition Analysis

![](https://cdn.w600.comps.canstockphoto.com/employee-retention-word-cloud-clipart_csp40856314.jpg)

- Attrition is a big concern for IT Companies. The term **Attrition** refers to a gradual but deliberate reduction in staff numbers that occurs as employees retire or resign and are not replaced.


- Attrition happens for several reasons, including pay, lack of growth, and poor workplace conditions. The term is also sometimes used to describe the loss of customers or clients as they mature beyond a product or company's target market without being replaced by a younger generation.


- Industry analysts anticipate a 22-23% attrition rate in 2021, which works out to one million resignations on a projected base of 4.6 million IT employees.


- This analysis is done based on the Attrition Dataset of an IT Firm based out of India

This directory contains 3 files

 **1.  HR_Attrition_EDA.ipynb** -> The Jupyter notebook having the code. \
 **2. HR_Attrition_Deck.pptx** -> The Presentation analyzing the various factors that constituted to the attrition. \
 **3. HR_Attrition_Recording.mp4** -> A video recording explaining the analysis. 
 
 
#  **Problem Statement**
---

- The dataset contains data of 1473 employees' exit survey who left the organization in the last 5 years. 

- We will analyse on the various factors that constitute around an employee in his/her workspace and predict whether a current employee will attrite or not 

- We will also look into certain factors that can be improved to bring down the attrition in the future


---

# ** Data Acquisition & Description**
---

- This section is emphasised on the accquiring the data and obtain some descriptive information out of it.

- There are **30 columns** associated with the dataset describing the information of the employees


|Id|Feature|Description|
|:--|:--|:--|
|01 | Age                    | Age of the user in years. |
|02 | BusinessTravel         | Whether the employee needs to travel during work hours. |
|03 | Department             | Last worked department of the employee. |
|04 | DistanceFromHome       | Employee's distance between Office and Home. |
|05 | Gender                 | Gender of the employee. |
|06 | JobInvolvement         | Employee's involvement in work on a scale of 1 - 5. |
|07 | JobLevel               | Organization Level where employee was working. |
|08 | JobRole                | The last working role of the employee. |
|09 | JobSatisfaction        | Was the employee satisfied with the job when he/she left the organization. |
|10 | MaritalStatus          | The Marital status of the employee. |
|11 | MonthlyIncome          | The monthly income of the employee in Rupees. |
|12 | NumCompaniesWorked     | The companies worked prior joining this Organization. |
|13 | OverTime               | Whether the employee has worked overtime. |
|14 | PercentSalaryHike      | The average percentage of Salary Hike given to the employee anually. |
|15 | PerformanceRating      | The latest performance rating given to the employee. |
|16 | StockOptionLevel       | The various option approval levels entitled to the employee. |
|17 | TotalWorkingYears      | The Years of Experience of the Employee in Years. |
|18 | TrainingTimesLastYear  | The number of Mandatory and Self-Enrolled Trainings attended by the employee in hours. |
|19 | YearsAtCompany         | The Employee's Work Years in the Organization. |
|20 | YearsSinceLastPromotion| The Employee's latest year since his last promotion before attrition. |
|21 | YearsWithCurrManager   | The Employee's association with their current manager before attrition. |
|22 | Higher_Education       | The Employee's Highest Education qualification. |
|23 | Date_of_Hire           | The Employee's hire date in dd-mm-yyyy format. |
|24 | Status_of_leaving      | Employee's reason for leaving the organization. |
|25 | Mode_of_work           | The mode of work for the employee. |
|26 | Leaves                 | The leaves allocated to the employee. |
|27 | Absenteeism            | The leaves utilized by the employee. |
|28 | Work_accident          | Whether the employee was involved in any kind of work accident. |
|29 | Source_of_Hire         | The source used by the employer to hire the employee. |
|30 | Job_mode               | Employment status of the employee. |


