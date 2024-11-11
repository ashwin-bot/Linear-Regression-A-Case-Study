# Simple Linear Regression : A Case Study
A Study of Simple Linear Regression Algorithm with some notes from college course work , and simple linear regression projects for acadacademic purposes.
## Table of Content :
**- Introduction**  
**- Assumptions of Simple Linear Regression**  
**- Best Fit Line**  
**- Evaluation Metrics of Simple Linear Regression**  
**- Process of Performing Simple Linear Regression**
### Introduction :
Simple Linear Regression is an supervised learning algorithm that is used to analyze the relationship between two quantitative variables. Here one variable (the independent variable , X) is used to predict the value of another variable (the dependent variable, Y). The goal of linear regression is to find the best-fit line through a set of data points, which minimizes the difference between the predicted values and the actual values.  
In simple linear regression, the relationship between X and Y is expressed with the equation of a line:
![image](https://github.com/user-attachments/assets/8975f167-fbca-4775-9889-cdf21e75c860)
### Assumptions of Simple Linear Regression :
1. Linearity : The relationship between the independent variable(s) and the dependent variable is linear. This means that changes in the predictor(s) should result in proportional changes in the response variable.
2. Independence : The observations in the dataset are independent of each other. This means that the value of the dependent variable for one observation does not depend on the value of the dependent variable for another observation. 
3. Normality : The residuals should be normally distributed. This means that the residuals should follow a bell-shaped curve.
4. Homoscedasticity : Across all levels of the independent variable(s), the variance of the errors is constant. This indicates that the amount of the independent variable(s) has no impact on the variance of the errors.
### Best Fit Line :
Our primary objective while using linear regression is to locate the best-fit line, which implies that the error between the predicted and actual values should be kept to a minimum. There will be the least error in the best-fit line.  
The best Fit Line equation provides a straight line that represents the relationship between the dependent and independent variables. The slope of the line indicates how much the dependent variable changes for a unit change in the independent variable(s).
![Best_Fit_Line](https://github.com/user-attachments/assets/cd667600-4c08-44df-b480-816b2dcfebfa)
## Evaluation Metrics of Simple Linear Regression :
1. Mean Absolute Error (MAE) : MAE measures the average absolute difference between the predicted values and the actual values.
![image](https://github.com/user-attachments/assets/a48202f8-6abb-49ef-931a-524c7d3261f5)
2. Mean Squared Error (MSE) : MSE calculates the average of the squares of the errors, which emphasizes larger errors more than smaller ones.  
![image](https://github.com/user-attachments/assets/5feb87b0-026b-46b8-a569-624c5a99a233)
3. Root Mean Squared Error (RMSE) : RMSE is the square root of MSE, bringing it back to the same unit as the target variable.
![image](https://github.com/user-attachments/assets/8b4dea83-9dda-4c7e-bfa5-4f64943f7232)
4. R-Squared (Coefficient of Determination) : R-squared measures the proportion of variance in the dependent variable that can be explained by the independent variable(s).
![image](https://github.com/user-attachments/assets/01fe19ef-b1a8-4d68-9bfb-db3d8e521f70)  
where RSS is the residual sum of squares and TSS is the total sum of squares.
### Process of Performing Simple Linear Regression :
1. Collect and Prepare the data : Gather data that contains both the independent and dependent variables. Handle missing values, remove outliers, and correct inconsistencies. Good data quality is crucial for an accurate model.
2. Explore the Data : Use scatter plots to visualize the relationship between X and Y. A linear pattern indicates that simple linear regression is a good fit. The correlation coefficient helps measure the strength and direction of the relationship. A correlation close to ±1 suggests a strong relationship, while a value near 0 suggests a weak or no relationship.
3. 


