Not all the models have the same metrics. So it is quite important to understand the metrics of each of the models.

Below are three error metrics that are commonly used for evaluating and reporting the performance of a regression model; they are:
Mean Squared Error (MSE).
Root Mean Squared Error (RMSE).
Mean Absolute Error (MAE)

# Coefficient of Correlation (R):
ossible values of the correlation coefficient range from -1 to +1, with -1 indicating a perfectly linear negative, i.e.,
inverse, correlation (sloping downward) and +1 indicating a perfectly linear positive correlation (sloping upward)

# Coefficient of Determination (R Squared): 
R2 shows how well terms (data points) fit a curve or line. R2 values range from 0 to 1 and are commonly stated as percentages from 0% to 100%.
An R2 of 100% means that all movements of a security (or another dependent variable) are completely explained by movements in the index (or the 
independent variable(s) you are interested in.

# What Is the Difference Between R-Squared and Adjusted R-Squared? 
The most vital difference between adjusted R-squared and R-squared is simply that adjusted R-squared considers and tests different
independent variables against the model and R-squared does not. You only need R2 when working with samples. In other words, R2 isn’t necessary 
when you have data from an entire population.

<img width="237" alt="image" src="https://user-images.githubusercontent.com/31846843/172531437-3dd5ca20-3b55-41d6-a850-d7dbd7371faa.png">

there is one main difference between R2 and the adjusted R2: R2 assumes that every single variable explains the variation in the dependent variable. 
The adjusted R2 tells you the percentage of variation explained by only the independent variables that actually affect the dependent variable. 
The adjusted R2 will compensate for this by that penalizing you for those extra variables.
