User loan Prediction
Getting a loan may take quite a time and take effort of bank employees to make the right decision, in our project we want to solve this problem by making a loan prediction system that will predict if user is worth the loan or not.
A banking system that predicts if a user is entitled to receive a loan, based on a set user data stored in the dataset.


 The data contains more than 5000 rows and 14 attributes specific to the customer’s personal data, this data is processed by Preprocessing operations https://www.kaggle.com/krantiswalke/bank-personal-loan-modelling


The algorithm we followed has two stages:
1.	Processing the entered data, the input of this algorithm is our Dataset (70% training and 30% testing). This data processed by Data Preprocessing, which it works to convert raw data into ready-made data, which is the most important process that ensures the coordination of large data sets in a way through which the existing data can be interpreted, one of the most important preprocessing operations is the data cleaning process (filling in missing values, deleting duplicate lines, etc..).
2.	After processing, the data is entered into one of the models that we will know in the next paragraph, we are watching the output.


Finally, we solved the loan prediction problem using Machine Learning techniques. We chose the three most used models and conducted the experiment on the existing dataset, in order to test which of the three techniques are better in terms of results. Naive Bayes algorithm was the best of the three techniques.
