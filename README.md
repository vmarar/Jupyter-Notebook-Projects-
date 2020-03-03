# Lending-Club-Analysis

The goal of this project was to identify what borrower features can be used to predict Loan interest rates. 

The data was preprocessed (special characters were removed, data types were converted, missing values were imputed and outliers were treated and checked using IQR )

Z-score was used to check for outliers in each of the columns as well and remove any remaining outliers that IQR did not account for. 
Using visualization as well as calculating the correlation between other variables and ‘INTEREST RATE’ , I was able to select appropriate variables for Linear Regression Analysis. 

Using ‘INTEREST RATE’ (dependent variable), and ‘AMOUNT REQUESTED’ and ‘FICO SCORE’ as independent variables, I was able to define a multivariatelinear regression model. 

I then used a OLS Summary to understand the results and understand the impact of individual variables on the dependent variable. I analyzed P-Values, Coefficents, R-Squared, and F-Stat/Test

Overall the model is a good fit per the parameters discussed above, although parameters such as the standard error of the coefficents and condition number indicate multicollinearity between the independent variables. In this case further analysis using VIF, and a larger data set can be used to improve the model and reduce multicollinearity.
