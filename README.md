# Kaggle-Titanic-Competition

This is a competition dataset from Kaggle. Reference: https://www.kaggle.com/c/titanic/data

2 files train.csv and test.csv are provided. Use the train dataset to build model and predict the outcome (whether the passenger can survive or not) on the test dataset

Variable | Definition | Key
---------|-----------|-------
survival | Survival	| 0 = No, 1 = Yes
pclass | Ticket class	| 1 = 1st, 2 = 2nd, 3 = 3rd
sex | Sex
Age | Age in years
sibsp | # of siblings / spouses aboard the Titanic
parch | # of parents / children aboard the Titanic
ticket | Ticket number
fare | Passenger fare
cabin | Cabin number
embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton

**Variable Notes**

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

**Algorithm result:**

![Alt Text](https://github.com/lxy000719/Kaggle-Titanic-Competition/blob/master/Titanic/image/3.png)

**Some graphical analysis:**

![Alt Text](https://github.com/lxy000719/Kaggle-Titanic-Competition/blob/master/Titanic/image/1.png)

![Alt Text](https://github.com/lxy000719/Kaggle-Titanic-Competition/blob/master/Titanic/image/2.png)







