# Week_7_Group_Work
1. Create an account on lucidchart.com and create an ERD diagram for the following scenario:
A grocery store owner would like to store all their data in a database. Some important facts you need to include are
  - The owner has multiple stores
  - The owner has multiple employees and the managers report to him, but all other
     employees report to store managers
  - The store has a membership program, but not all customers need to be members

[Week_7_Group_Work.pdf](https://github.com/apate305/Week_7_Group_Work/files/7438507/Week_7_Group_Work.pdf)
![Week_7_Q1](https://user-images.githubusercontent.com/69228806/139365717-22858c2f-3c20-4c60-9a64-3658e3b772be.png)

2. With your group, create a list of at least 5 and no more than 10 ways data can be “dirty”. Perhaps think back to some data sets we have used that have had weird stuff in them. Discuss how you would resolve each of these and briefly explain.

"Dirty Data"
    1) Empty cells--these cells provide no significant information and merely take up unnecessary space.
    2) Different Datatypes within a column--This would show poor organizaton of data and more importantly commands would not be carried out
       properly on these kinds of columns.
    3) Spaces in column names or values--this would imply that there is an error in the creation process of the database. Calling on the values
       or column names would be difficult if the user does not know about the spaces present.
    4) Extra or faulty characters--Example: if the same person is referenced in the database but with a different spelling of their name, then
        running codes on these columns would output errors.
    5) Duplicates of entire rows--this serves no purpose and provides no significant information. Duplicate values are okay as they may reference
       different things. 


3. Look at the requirements for the exploratory data analysis project. List at least 2 APIs that have data interesting to you. Please pick at least one API that’s not listed in the project instructions.
    1) API from the list--> Crime Data: https://crime-data-explorer.fr.cloud.gov/api
    2) API not on list--> Poverty Estimates: https://www.census.gov/programs-surveys/saipe/data/api.html
