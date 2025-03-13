# Boston-Housing-Market-Predictions
Actionable Insights and Recommendations
1. Performed EDA, univariate and bivariate analysis, on all the variables in the dataset

2. Then used a zscore threshold of >3 to detect and apply an outlier treatment using the relationship between variables.

3. Started the model building process with all the features.

4. Removed multicollinearity from the data and analyzed the model summary report to drop insignificant features where there (p-value > .05)

5. We checked for different assumptions of linear regression and fixed the model iteratively if any assumptions did not hold true.

Finally, we evaluated the model using different evaluation metrics such Rsquared(accuracy) and RMSE(error)

Lastly, the model equation is:

log(MEDV) = 3.0309 + -0.0763 CRIM + -0.0582 * NOX + 0.0866 * RM + -0.0787 * DIS + -0.0778 * PTRATIO + -0.1944 * LSTAT

After interpreting this linear regression equation, it is clear that the number of rooms had a strong correlation with our target variable, MEDV. That allowed us to create a sufficient baseline variable in our prediction model to help us predict the prices of homes in the Boston Metropolitan Area and have a normal distribution with our test set on the unseen data. Although, our final model had an Rsquared of .75% accuracy on our test set, I believe adding more complexity to the model by introducing more features could potententially allow us to increasing the accuracy of our prediction model even further.
