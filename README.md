# Titanic Survival Analysis

## Project Overview
This project aims to analyze the survival patterns of passengers aboard the Titanic, one of the most infamous shipwrecks in history. The analysis leverages the Titanic dataset, which contains details about the passengers such as age, gender, passenger class, and survival status. By performing exploratory data analysis (EDA), we uncover insights into factors that influenced survival rates during the tragedy.

---

## Dataset 

### Dataset Link: https://www.kaggle.com/datasets/yasserh/titanic-dataset

The dataset used for this analysis is the *Titanic dataset*, which includes the following features:
- *PassengerId*: Unique identifier for each passenger.
- *Survived*: Survival status (0 = Not Survived, 1 = Survived).
- *Pclass*: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- *Name*: Name of the passenger.
- *Sex*: Gender of the passenger.
- *Age*: Age of the passenger.
- *SibSp*: Number of siblings/spouses aboard.
- *Parch*: Number of parents/children aboard.
- *Ticket*: Ticket number.
- *Fare*: Fare paid for the ticket.
- *Cabin*: Cabin number (if available).
- *Embarked*: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

---

## Insights Derived
The following insights were derived from the analysis:

### 1. Survival Rate by Gender
- Females had a significantly higher survival rate compared to males.
- This suggests that during the evacuation, women were prioritized for lifeboats as part of the "women and children first" protocol.

### 2. Survival Rate by Passenger Class
- First-class passengers had the highest survival count, followed by second and third-class passengers.
- This highlights the social disparity in access to safety during the disaster.

### 3. Age and Survival
- Younger passengers, particularly children, were more likely to survive.
- The median age of survivors was lower compared to non-survivors, indicating prioritization of children during rescue efforts.

---

## Visualizations
The analysis was supported by the following visualizations:
1. *Survival Rate by Gender*: A bar plot comparing survival rates between males and females.
2. *Survival Count by Passenger Class*: A count plot showing the survival count for each passenger class.
3. *Age Distribution of Survived vs. Not Survived*: A box plot highlighting the age ranges of survivors and non-survivors.

---

## Conclusion
This analysis sheds light on the societal and operational dynamics during the Titanic disaster. Gender, passenger class, and age were significant factors influencing survival rates. These findings provide historical insights and help in understanding human behavior and decision-making in crisis situations.

---

## Requirements
- *Python 3.8+*
- *Libraries*:
  - pandas
  - matplotlib
  - seaborn
  
Install the libraries using:
```bash
pip install pandas matplotlib seaborn
