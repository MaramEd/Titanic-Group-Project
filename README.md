# Surviving The Titanic: Group Project

## Problem Statement
To predict the survival rate of the Titanic passengers.


## Data Understanding
In this section, a complete overview of the data is provided, such as the number of variables, missing percentages, data size, and categorical and numerical column types.


### Variable Description:

- Survived: Survivors (1) or Non-survivors (0)
- Pclass: Passenger's class: 1st class(1), 2nd class (2) and 3rd class (3)
- Name: Passenger's name
- Sex: Passenger's sex
- Age: Passenger's age
- SibSp: Siblings/spouses aboard
- Parch: Parents/children aboard
- Ticket: Ticket number
- Fare: Fare
- Cabin: Cabin
- Embarked: Port of embarkation: Cherbourg (C), Queenstown (Q) and Southampton (S)

## Data Preparation
#### Outliers Analysis
#### Discovering Outliers with Visualization Tools

Box plots are used to depict groups of numerical data graphically through their quartiles. Outliers are plotted as individual points.


### Feature Engineering
In this section, the dataset is prepared to be more compatible with the machine learning algorithm requirements. This process should improve the model’s performance.

#### Imputation

Imputation is performed to preserve the size of the data and improve the model’s performance.

## Data Modeling
In this section, a model will be created to predict the survival rate of the Titanic passengers.


## Conclusion
<p style='text-align: justify;'> The features were standardized and split using the train-test-split function. The following models were used: decision trees, random forests, bagging, and support vector machine. However, k-nearest neighbors yielded the best results in terms of predicting the survival rate of the passengers of Titanic, the sinking ship, on Kaggle (0.80382). </p>

### Group Members: 
Maram, Mohammed, Sara, Saud.
 
