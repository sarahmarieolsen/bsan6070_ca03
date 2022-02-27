# bsan6070_ca03 readme

**Decision Tree Algorithm to Predict Income Class**

*Introduction:*
In this project, a decision tree algorithm is implemented to predict whether the income of a person is greater than or less than 50k. The data was sourced from the US Census. There are seven categorical independent variables that factor into the outcome of the prediction. The independent variables include capital gain or loss, age, education, occupation, marital status, race and sex, and hours of work per week; the dependent variable, signaling the outcome of the prediction is labeled 'y'. If y == 1, then a person is predicted to have an income greater than 50k.

*Process:*
First, the data is cleaned and prepared for analysis. This process entails checking for null values and separating the original data into a test set and training set. The data is also asessed for quality using matplotlib's stacked bar chart to visualize the seven explanatory variables with respect to the outcome varaible. The decision tree is implemented using scikitlearn's DecisionTreeClassifier. The first fuction method used to measure the quality of the split is entropy and the second uses gini impurity. For each of these split types, the hyperparameters are manually tuned four times each. The model with the highest accuracy score is selected for use in making predictions. Finally, the best model is used to make a prediction using a new record.
