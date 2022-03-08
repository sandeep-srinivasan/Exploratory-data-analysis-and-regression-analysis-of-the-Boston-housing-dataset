# Exploratory-data-analysis-and-regression-analysis-of-the-Boston-housing-dataset

The Boston data set has 506 rows and 14 columns. The rows in the dataset represents the number of cases or values. The columns represents the variables or the attributes.

The pairwise scatterplots of the predictors in the data set were plotted. The correlation matrix and the p values associated with the variables are as shown,

![image](https://user-images.githubusercontent.com/42225976/157336172-d1caff62-1200-4767-b52d-3e51dd8ec121.png)

![image](https://user-images.githubusercontent.com/42225976/157336224-913f3b20-01e1-406a-8dc4-6a1c672a3625.png)

The correlation of various attributes with the medv is as shown above. If the values of correlation > + or - 0.4, it is considered as having strong relationship and has been retained in the scatterplot shown above.

Summary of crimes rates related to number of suburbs is,

![image](https://user-images.githubusercontent.com/42225976/157336983-85864528-e6b8-49ca-b01f-3701224ff4bc.png)

Since the max value of crim is significantly higher than the median, there certainly seems that there are few suburbs which have particularly high crime rates.

The histogram of crimes rates v/s number of suburbs is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337769-8b963558-107d-4d12-b301-2ffb84d9bdb0.png)

From the histogram, we can consider the crime rates to be high if it crosses 30 crime rates in the Boston suburub and there are 8 suburbs with crim rates more than 30 and hence are very high.

Summary of crime rates related to tax rates are,

![image](https://user-images.githubusercontent.com/42225976/157337168-5d025e14-c0a5-4b7a-88d2-523e4f562e52.png)

Since the max value of crim is significantly higher than the median, there certainly seems that there are few suburbs which have particularly high tax rates.

The histogram of crimes rates v/s high tax rates is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337235-61123e45-d9f4-40c0-8dee-999c7cd46e6d.png)

From the histogram, we can consider the taxes to be high if it crosses a value of 500. There are 137 suburbs with tax rates more than 500 and hence are very high.

Summary of crime rates related to pupil-teacher ratio are,

![image](https://user-images.githubusercontent.com/42225976/157337323-8761a3a4-2c9c-4135-b762-5610249ea9fd.png)

We can see that the max value is slightly higher than the 3rd quartile, therefore anything greater than that has high ptratio.

The histogram of crimes rates v/s pupil-teacher ratio is plotted as shown,

![image](https://user-images.githubusercontent.com/42225976/157337391-f9c1a1fe-e0df-49fa-bf6e-93adc9951ba6.png)

The histogram also reinstates the same regarding high ptratio. 
