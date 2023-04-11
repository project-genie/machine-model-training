# Training the machine model.

Dataset is generated via the repo: https://github.com/project-genie/python-database-composer-script

Dataset consisting of three important variables: "user_level", "task_difficulty", and "hours".

Every user has a "level" variable, and every task has a "difficulty".

Then the dataset is exported to a .csv file (completed_tasks.csv).

Data cleaning is done via checking null values, clearing outliers etc.

Running regression model on the dataset.

According to our dataset, Polynomial Regression was the best fit.
![Polynomial Regression](./polynomial.png)

Based on the parameters, model calculates the hours and return the predicted value.
