<h1>Key Takeaways</h1>

<h2>Model Used</h2>
<h3>Linear Regression Model</h3>
 <p>Linear Regression Model is a statistical method used to understand the relationship between two or more variables. It's often used in predictive modeling and data analysis. 
 
<strong>Variables</strong>:

Independent Variable (X): This is the variable you think is influencing another variable. For example, in our dataset store, item, and date are the independent variables.
Dependent Variable (Y): This is the variable that you think is being influenced by the independent variable. In our example, sales is the dependent variable.

<strong>Relationship</strong>:

Linear regression looks for a linear relationship between the independent and dependent variables. This means it tries to fit a straight line through the data points.

<strong>Equation of a Line</strong>:

The simplest form of a linear regression model is a straight-line equation:

𝑌=𝑚𝑋+𝑏

Here:
Y is the dependent variable.
X is the independent variable.
m is the slope of the line (how much Y changes for a unit change in X).
b is the y-intercept (the value of Y when X is 0).

<h2>Model Evaluation Methods Used</h2>
<h3>Mean Absolute Error (MAE)</h3>
MAE is the average of the absolute differences between the predicted values and the actual values. It gives us an idea of how much the predicted values deviate from the actual values on average.

Formula:
MAE=1/𝑛 ∑ |𝑦_pred - y_actual|
Interpretation:
A smaller MAE indicates a better fit of the model.

<h3>Mean Squared Error (MSE)</h3>
MSE is the average of the squared differences between the predicted values and the actual values. Squaring the differences gives more weight to larger errors.

Formula:
MSE=1/𝑛 ∑ |𝑦_pred - y_actual| ^2
 
Interpretation:
Since the differences are squared, MSE penalizes larger errors more than smaller ones.

<h3>Root Mean Squared Error (RMSE)</h3>
RMSE is the square root of the MSE. It provides a measure of the average magnitude of the error, with the same units as the data.

Formula:
RMSE= (1/𝑛 ∑ |𝑦_pred - y_actual| ^2)^1/2
​
Interpretation:
Like MSE, it penalizes larger errors more than smaller ones, but it’s easier to interpret since it’s in the same units as the data.

<h3>R-squared (R²)</h3>
R² is a statistical measure that represents the proportion of the variance for a dependent variable that's explained by the independent variable(s) in the model. It ranges from 0 to 1.



