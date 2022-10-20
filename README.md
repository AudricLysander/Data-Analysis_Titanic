# Data Analysis: Titanic

## Dataset Explanation
The Titanic dataset is a dataset obtained from one of the most famous shipwrecks in history, the Titanic.

On her maiden voyage on April 15, 1912, the RMS Titanic was deemed the "unsinkable" ship that sank due to a collision with an iceberg. Unfortunately, there were not enough lifeboats to accommodate all the passengers.

While there is a lot of luck going into survival, it seems that some groups of people are more likely to survive than others.

Dataset Source: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

## Explanation of Data Analysis
At this stage, data exploration will be carried out which includes preprocessing. So that every feature of the explored data will be clean from Null Values and each feature will have a data type that matches the data dictionary. Data exploration is carried out in several stages and is carried out based on data groups.

## Feature Description
survive = Passengers who are survive or not survive
pclass = Class of ticket
sex = Passenger gender
age = Passenger age in years
sibsp = # of siblings / spouses aboard the Titanic
parch = # of parents / children aboard the Titanic
fare = Passenger fare
embarked = Port of Embarktion
class = Class of ticket
who = Call for passengers
adult_male = Adult male passenger
deck = Passenger deck
embarked = Port of Embarktion
alive = Passengers who are survive or not survive
alone = Single passenger

## Summary
1. The Titanic passengers who did not survive were 62% (549 passengers) and those who survived were 38% (340 passengers) with a total of 889 passengers.

2. There is a low correlation between sibsp column with parch and fare, and parch column with fare. From this correlation, it can be concluded that
- Most of the passengers who survived were passengers who traveled alone or with 1-2 family members and/or were 22 years old.
- Most of the passengers who did not survive were passengers who went with more than 4 family members and/or bought tickets for under 20 pounds and/or were around 27 years old.

3. There is no correlation between categorical data, but there is information that can be seen
- Many of the passengers who did not survive came from passengers who had third class tickets, while many of the survivors came from frist class tickets.
- More male passengers died than female passengers.
- More than half of passengers departing from Southampton did not survive and compared to 2 other port.
- Passengers who survived Cherbourg more than passengers who did not survive. When compared to other port, the port of Cherbourg is the only port that has a higher level of passenger survive compared to passengers who did not survive.
