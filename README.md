## Salary Prediction Project (Python)

### Goal
Recruiting process is not easy for company, especially it is a crucial task for the HR department. Therefore, this project aims to analyze job features that affect one's salary in order to optimize the salary compensation strategy. The result will show the optimal range of salary for different job position based on years of experience, distance to work location, and education level. We are also going to use machine learnning models to predict the estimate of employee's salary. 

### Steps
- Define: Clarify the problem
- Discover: Data processing, Data Cleanning, Exploratory Data Analysis to examine the distribution and correlation
- Develop: Create the model using **linear regression, random forest, and gradient boosting** methods.

### Model Results
#### Under Cross Valication, we get the MSE as following:
- Linear Regression: 383
- Random Forest: 442
- Gradient Boosting: 357

### Conclusion
Gradient Boosting results the best model with the lowest MSE. 
Also, we discovered that job position, years of experiences, and distance to work are three most important factors that affect one's salary.

