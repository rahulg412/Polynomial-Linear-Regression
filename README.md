# Polynomial-Linear-Regression

Used LinearRegression and PolynomialFeatures class to predict non-linear values.
Problem: Predcit current Salary of a newly hired person based on the experience, haivng data from previous employer.

Step 1: Import reuqired libaries
        numpy
        andas
        matplotlib
        sklearn.preprocessing
        sklearn.linear_model
       
Step 2: Create dataset by reading csv file.
        Extract matrix of feature of independent variable from dataset.
        Extract vector of dependent variable from dataset.
        
Step 3: For comparing the result of Polynomial Linear Regression with respect to Linear Regression, both of the regressor created.
        Create Linear Regressor to predict the current salary of the newly hired person.
        
Step 4: Create Polynomial feature of matrix using PolynomialFeatures class from sklearn.preprocessing using degree paramneter (it specify           which order of degree need to be created from indepedent variable, it will add addition 1st coloum having value 1 for all the               observations for bias, y = b0 + b1X1 + b2X2).
        
        use LinearRegression regressor on the extracted polynomial features to make correlation between independent and dependent variable.

Step 5: Create scatter plot for original dataset and create plot of created regressor model and compair the results from LinearRegression           and Polynomial Linear Regression. if data is not linear then Polynomial Linear Regression would be best fit as compaired to Linear         Regression.

Step 6: Based on the value of the degree parameter in PolynomialFeatures you can create model which can fit to the observation points.
