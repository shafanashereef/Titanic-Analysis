# Titanic Dataset – Query Practice Project

## Introduction
This project focuses on practicing data filtering, conditional selection, and querying techniques using the Titanic dataset. The dataset contains passenger information, including age, gender, travel class, fare, and survival status. The purpose of this practice is to improve data manipulation skills using pandas in Python by applying various logical and conditional queries.

---

## Dataset Information

- **Rows:** 891  
- **Columns:** 12  

### Data Types
- **Integer:** 5  
- **Float:** 2  
- **Object:** 5  

### Missing Values
- **Age:** 177  
- **Cabin:** 687  
- **Embarked:** 2  

---

## Dataset Description

| Column Name   | Description |
|---------------|-------------|
| **PassengerId** | Unique identifier for each passenger |
| **Pclass** | Passenger class (1st, 2nd, 3rd) |
| **Name** | Full name of the passenger |
| **Sex** | Gender of the passenger |
| **Age** | Age of the passenger |
| **SibSp** | Number of siblings/spouses aboard |
| **Parch** | Number of parents/children aboard |
| **Ticket** | Ticket number |
| **Fare** | Ticket fare |
| **Cabin** | Cabin number |
| **Embarked** | Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton) |
| **Survived** | Survival status (0 = No, 1 = Yes) |

---

## Null Value Handling
- **Age:** Filled using median
- **Cabin:** Replaced with `"Unknown"` due to a high number of missing values  
- **Embarked:** Filled using mode (Most passengers embarked from S (Southampton))  

---

## Query Tasks Practiced

1. Get the details of passengers who survived and were younger than 18 years old.  
2. Get the details of male passengers who were older than 40 years old.  
3. Get the details of passengers who paid a fare greater than $30 and survived.  
4. Get the details of female passengers who did not survive.  
5. Get the details of passengers who were in either the first or second class.  
6. Get the details of passengers who had more than two siblings/spouses aboard the Titanic and did not survive.  
7. Get the details of passengers who were in the third class and were older than 30 years old.  
8. Get the details of passengers who were younger than 15 years old and had parents/children aboard.  
9. Get the details of male passengers who paid less than $10 for their fare.  
10. Get the details of passengers who were in the third class, younger than 20, and had siblings/spouses aboard. 
11. Get the details of passengers who were either younger than 10 years or older than 60 years, and survived.  
12. Get the name, passenger ID, and ticket number of female passengers who embarked in Southampton.  
13. Get the names of male passengers who survived.  
14. Get the name, passenger ID, and cabin number of passengers who were in the second class and paid a fare greater than 50.  
15. Get the details of passengers who were embarked in Cherbourg or older than 50 years.  
16. Get the details of passengers between 3 to 10 years old.  
17. Get the details of male passengers who survived or female passengers who did not survive.  
18. Get the passenger ID, name, and class of passengers who embarked in Queenstown and survived.  
19. Get the details of passengers who had more than 2 siblings/spouses aboard or fewer than 2 parents/children aboard.  
20. Get the details of male passengers who embarked in Southampton.  
21. Get the name, age, ticket, cabin number, and fare of female passengers who were embarked in Queenstown.  
22. Get the details of passengers who were in the first class.  
23. Get the details of female passengers who had more than 3 siblings/spouses aboard.  
24. Get the details of male passengers who were either younger than 18 or older than 60.  
25. Get the details of passengers who were in the second class, older than 50, and had parents/children aboard.  

---
