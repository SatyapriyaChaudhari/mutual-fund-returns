### Project Overview

 The data given is of the mutual funds in USA. The objective of this problem is to predict the ‘basis point spread’ over AAA bonds i.e. feature ‘bonds_aaa’ against each Serial Number.

Basis Point Spread indicates the additional return a mutual fund would give over the AAA rated bonds.


### Learnings from the project

 Apply linear model using GridsearchCV. Concepts utilised

- [ ] Chi square contengency test
- [ ] Box plot
- [ ] Linear regression
- [ ] GridsearchCV
- [ ] Ridge and Lasso Regressor


### Approach taken to solve the problem

 Steps involved:
1. Perform Chi-Square test to check assosciation between features and remove the same so that the assumption for linear regression model is satisfied.
2. Check for Outliers.
3. Apply the linear regression model.
4. Use lasso regressor and ridge regressor with the help of gridsearch cv , and check is there any improvement in the prediction.


