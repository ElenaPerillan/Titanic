# Titanic

This exercise aims to develop a machine learning model to predict the survival probability of Titanic passengers. By analyzing various passenger attributes such as age, gender, class, and other relevant features, the model will identify patterns and factors that influenced survival rates. Utilizing techniques like data preprocessing, feature engineering, and model evaluation, this project seeks to provide insights into the tragic event and demonstrate the power of machine learning in predictive analytics. The end goal is to create an accurate and reliable model that can be used for educational purposes to enhance understanding of data analysis.

Features description:

- **PassengerId**: A unique identifier assigned to each passenger.

- **Survived**: Indicates whether the passenger survived (1) or did not survive (0).

- **Pclass**: The passenger's class on the ship. It has three possible values:
  - 1: First Class
  - 2: Second Class
  - 3: Third Class

- **Name**: The full name of the passenger.

- **Sex**: The gender of the passenger. It is either 'male' or 'female'.

- **Age**: The age of the passenger in years. Some entries contain fractional values for ages less than 1 year. If the age is unknown, it may be represented as a NaN (Not a Number).

- **SibSp**: The number of siblings or spouses the passenger had aboard the Titanic. Siblings are defined as brothers, sisters, stepbrothers, and stepsisters. Spouses are defined as husbands and wives (mistresses and fiancés were ignored).

- **Parch**: The number of parents or children the passenger had aboard the Titanic. Parents are defined as mother and father. Children are defined as son, daughter, stepson, and stepdaughter. 

- **Ticket**: The ticket number of the passenger.

- **Fare**: The amount of money the passenger paid for the Titanic ticket.

- **Cabin**: The cabin number where the passenger stayed. This field contains many missing values.

- **Embarked**: The port where the passenger boarded the Titanic. It has three possible values:
  - C: Cherbourg
  - Q: Queenstown
  - S: Southampton
