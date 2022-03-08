# Exploratory-data-analysis-and-regression-analysis-of-the-Boston-housing-dataset

The Boston data set has 506 rows and 14 columns. The rows in the dataset represents the number of cases or values. The columns represents the variables or the attributes.

The pairwise scatterplots of the predictors in the data set were plotted.
Pairwise scatterplots of crime rate vs the first six predictors are,

![image](https://user-images.githubusercontent.com/42225976/157339037-806dc58d-9960-4c90-bdf4-b1d1eb10d4c1.png)

Pairwise scatterplots of crime rate vs the last seven predictors are,

![image](https://user-images.githubusercontent.com/42225976/157339088-72d3fe3f-3776-4bd9-b7f4-f2a44bbf8301.png)

The correlation matrix and the p values associated with the variables are as shown,

![image](https://user-images.githubusercontent.com/42225976/157336172-d1caff62-1200-4767-b52d-3e51dd8ec121.png)

![image](https://user-images.githubusercontent.com/42225976/157336224-913f3b20-01e1-406a-8dc4-6a1c672a3625.png)

The correlation of various attributes with the medv is as shown above. If the values of correlation > + or - 0.4, it is considered as having strong relationship and has been retained in the scatterplot shown above.

Summary of crimes rates related to number of suburbs is,

![image](https://user-images.githubusercontent.com/42225976/157337769-8b963558-107d-4d12-b301-2ffb84d9bdb0.png)

Since the max value of crim is significantly higher than the median, there certainly seems that there are few suburbs which have particularly high crime rates.

The histogram of crimes rates v/s number of suburbs is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337972-b11e5e36-a786-4ea6-a798-703b2f601da6.png)

From the histogram, we can consider the crime rates to be high if it crosses 30 crime rates in the Boston suburub and there are 8 suburbs with crim rates more than 30 and hence are very high.

Scatterplots of crime rate, crim vs predictors are,

![image](https://user-images.githubusercontent.com/42225976/157339533-570983e6-9eb3-4d4e-b346-06ad0a741d9c.png)

Summary of high tax rates related to number of suburbs are,

![image](https://user-images.githubusercontent.com/42225976/157337168-5d025e14-c0a5-4b7a-88d2-523e4f562e52.png)

Since the max value of crim is significantly higher than the median, there certainly seems that there are few suburbs which have particularly high tax rates.

The histogram of high tax rates v/s number of suburbs is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337235-61123e45-d9f4-40c0-8dee-999c7cd46e6d.png)

From the histogram, we can consider the taxes to be high if it crosses a value of 500. There are 137 suburbs with tax rates more than 500 and hence are very high.

Summary of pupil-teacher ratio related to number of suburbs are,

![image](https://user-images.githubusercontent.com/42225976/157337323-8761a3a4-2c9c-4135-b762-5610249ea9fd.png)

We can see that the max value is slightly higher than the 3rd quartile, therefore anything greater than that has high ptratio.

The histogram of pupil-teacher ratio v/s number of suburbs is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337391-f9c1a1fe-e0df-49fa-bf6e-93adc9951ba6.png)

The histogram also reinstates the same regarding high ptratio. 

The plot of univariate regression coefficients v/s the multiple regression coefficients is,

![image](https://user-images.githubusercontent.com/42225976/157338637-816ecd0c-1e1c-4942-93d0-55c229d42a4d.png)

Estimated coefficients for the predictors in simple vs multiple linear regression are,

![image](https://user-images.githubusercontent.com/42225976/157339801-21509309-e45f-48d8-bdaa-3a6c1171a0e5.png)

When looking at the plot, we see that only for nox variable the estimate is abnormal.

Estimated coefficients for the predictors (except nox) in simple vs multiple linear regression are,

![image](https://user-images.githubusercontent.com/42225976/157339830-c6b38a51-b842-4cf0-93fc-558b4574a148.png)

Scatterplots of log(crim) vs predictors are,

![image](https://user-images.githubusercontent.com/42225976/157339963-9332fb18-c142-4556-ae0c-35b9c960b25b.png)

Using the log-transformed response the regression models are refit. The simple regression result, overall the values of the r squared and p-value (F-test) in the
fitted models improve significantly. For multiple regression result, the coefficient of nox becomes significant while the coefficient of dis becomes insignificant.
