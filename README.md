# Python_Project_Employee_DataAnalysis
The  dataset contains details of employees working in ABC company,consisting 458 rows and 9 columns.
The details of employees in the dataset are :
Name, Team, Number, Position, Age, Height, Weight,College and Salary
### Preprocessing Data
There were null values present in the columns "College" and "Salary" and those null values are changed to 'Unknown'
The column 'Height' is having incorrect data ,in the form of date. 
So the data in that column is changed with  random numbers between 150 and 180.

### Analyzing the dataset
1)  The team with more number of employees is Team 'New Orleans Pelicans' with 19 employees making 4.15% of the total employees.
    'Orlando Magic' and 'Minnesota Timberwolves' are the teams with least number of employees .Both team consists of 14 employees, each         makes 3.06% .
2)  There are 5 different employee positions : PG, SF, SG, PF & C with 102,100,92,85,79 employees respectively.
    Most of the employees belong to Position 'SG' with 102 employees, followed by 100 employees in 'PF' .
    
![111111](https://github.com/Srilekshmi-A/Python_Project_Employee_DataAnalysis/assets/138193879/596c57b4-9d18-49aa-b5be-fa888938f9b5)

3)  The employees in the company belongs to the age category 25 to 40
    We can see that 47 people belongs to age group 24 ,46 people belongs to age group 25,41 people are of age group 27 and so on.
    By analysing the top 10 maximum counts we can say that the majority of employees belongs to 22 to 30 age groups, with maximum from         age  group 24.

![2222222](https://github.com/Srilekshmi-A/Python_Project_Employee_DataAnalysis/assets/138193879/e31c392b-fb66-469b-bd46-d58470b39f5a)

4)  On sorting the Dataframe in descending order with respect to Salary we can conclude that : Position 'SF' and Team ' Los Angeles           Lakers' has the highest salary
5)  From this scatterplot we cannot say that there is a positive correlation between salary and age,as we can see in age group 35-40          salary is less mor majority of people.At the same time highest salary also belongs to age grop 35-40
     In all the age groups,there are employees with minimum salary and they form majority of the employees.
    So we can say that not only Age can determine the salary ,there can be many other factors also.

![33333](https://github.com/Srilekshmi-A/Python_Project_Employee_DataAnalysis/assets/138193879/722a3e4b-795b-44b7-aa37-64a584a62c65)

### Conclusion
The dataset of employees working in ABC company is preprocessed and analyzed.
Insights from the dataset are:
1) The team with more number of employees is Team 'New Orleans Pelicans' with 19 employees making 4.15% of the total employees.
'Orlando Magic' and 'Minnesota Timberwolves' are the teams with least number of employees .Both team consists of 14 employees, each makes 3.06%¶
2) Majority of the employees either belong to Positions SG ,PF or,PG
3) Majority of employees are from 22 to 30 age group, with maximum from age group 24.
4) The employee with the highest salary belongs to Position 'SF' and Team ' Los Angeles Lakers'.
5) We cannot determine the salary of a person by only considering their Age.There can also be many other factors that determine one's salary.











    
