# titanic_kaggle_comp
My first Kaggle competition, involving exploration, feature engineering, and model selection to classify the survival of passengers of the Titanic based on the classic Titanic dataset 

## Initial Feature Cleaning 
- encode male and female (1 and 0)
- drop passengerid, name, ticket and cabin
- encode C, Q and S (0, 1, 2)
- fill missing age with median of group with matching sex and class
- fill missing embarked with most common departure

## Exploration
- Did subsets of variables survive more?
- Can less important variables be transformed into more useful form?

## Feature Creation
- encode C, Q and S (0, 0, 1) embarked from S much higher survival rate
- SibSp to Binary of less than 2 or not, less than two much higher survival rate
- Parch less than 4 to 0, more than 4 has a low survival rate

## Enhanced Random Forest Classifier 
- new features 
- new grid search

## Gradient Boosting Machine
- same features
- different model and hyperparameters
