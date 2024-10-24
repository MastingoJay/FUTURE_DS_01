# FUTURE INTERNS-DATA-SCIENCE- TITANIC EDA PROJECT
Used jupyter notebook for analysis

![](https://github.com/MastingoJay/FUTURE_DS_01/blob/main/pic.jpg)

The aim of the project is to perform exploratory data analysis to uncover interesting patterns, insights, and potential anomalies within the Titanic dataset.
# Data Overview and Cleaning:
The dataset has 891 entries and 12 columns which are;

PassengerId

Survived

Pclass

Name

Sex

Age

SibSp

Parch

Ticket

Fare

Cabin

Embarked

# Analysis Overview
Data types are 2 float,5 int and 5 object.

Null and missing values are in the following columns age(177),cabin(687) and embarked(2).

Handling missing values - age i filled it with median,while for cabin i droped the whole column and embarked column i dropped the 2 null values.

The following columns had outliers,,fare leading with more then age then parch and lastly Sibsp

The following columns werent gonna be used and so i dropped them.They are PassengerId,Name and Ticket columns.

Total number of survived people is 340 while those that died was 549.

Total number per class was class 3 leading with 491,then class 1 which is 214 and lastly class 2 which is 184.

Total number as per gender is male leading with 577 and female 312

Maximum age of passengers is 80

Average age of passengers is 28.0

Minimum age of passengers is 0.42

Maximum fare paid by passengers is 512.33

Average fare paid by passengers is 14.45

Minimum fare paid by passengers is 0.0

# Visualizations Overview
1.Survival by passenger class showed that  there were high chances of survival in Pclass 1 while more chances of dying were in Pclass 3.

2.Survival per gender shows that female gender survived more than the male gender.

3.passengers class based on gender shows that in every Pclass there were more males than females.

# Correlation Matrix Overview
1.Positive correlated columns include;

Survived and fare

SibSp and Parch

SibSp and Fare

2.Zero correlated columns include;

Survived and Parch

Pclass and SibSp

Age and Fare

Parch and Pclass

3.Negative correlated columns include;

Survived and Pclass

Survived and Age

Survived and SibSp

Pclass and Age

Pclass and Fare

Age and SibSp

Age and Parch
