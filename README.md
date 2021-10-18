# regression

In this article, we are going to study the effect of more variables on measure of the fitness. 

regression of Sales on TV 

![image](https://user-images.githubusercontent.com/61835051/137634745-c19479f3-5b39-424b-8160-2014fb05f22c.png)


##Accuracy of the Model
Accuracy of the model is related to the standard errors, R2 and Residual Standard Error and F Statistics. a related table for single variable and multiple variables are shown here:

![image](https://user-images.githubusercontent.com/61835051/137634986-9acb8795-d5ba-4220-84c5-16d6920fa7e5.png) ![image](https://user-images.githubusercontent.com/61835051/137669105-b2257fc5-3c34-410c-a66f-c281c7a28b91.png)


Remember that RSE and RSS were calculated like this:

![image](https://user-images.githubusercontent.com/61835051/137635023-33355591-d6e5-49a2-bacc-0c9cca9f6b4d.png)

![image](https://user-images.githubusercontent.com/61835051/137635043-5a1d3649-f2ea-4072-a34e-3449fb08d0dc.png)

RSE depends on the units of Y. For example here RSE of 3.26, in thousand units will be 3,260 units, which implies that actual sales (Y) might deviate from the estimated one by 3,260 units. 

R^2 tries to unit free, and it is the measure of the explained error over total error. It is calculated like this: 
![image](https://user-images.githubusercontent.com/61835051/137635197-6c65af9b-a4a2-4c6e-92a2-a358ef9034cc.png)

##regression with respect to other variables seperately

![image](https://user-images.githubusercontent.com/61835051/137643212-46844ebf-3c35-4d49-94b2-70ea9e320ed3.png)

#Multiple regression of Sales on TV, Radio,and Newspaper
![image](https://user-images.githubusercontent.com/61835051/137643327-bc99e6d6-82a6-4f2a-b094-f3eba26cd908.png)

as it seen from the numbers, with multiple variables, the coefficients drops in absolute and nominal terms, so as the standard errors. The  associated t-statistics have increased as well, since the drop in std.errors is much larger. The multiple variable model is more significant than the simple one. 

In fact the decrease in std.error can be expected,as the more variables will give model to fit more closely and hence decrease the discrepancy.

The case of "Newspaper" is a bit problematic as it is seen from the table. This is due to the fact that actually  there was a high correlation between Radio and Newspaper. Like the bosses have increased or decreased the radio and newspaper budgets paralelly. 

# Stuation of R^2 and RSE with multiple variables.

adding a new variable will increase the R^2 , because the explained error will increase,and the total residual sum of squares will decrease. However, for some variables, this increase could be smaller. this will implies that this new variable is not that critical. 

RSE is the adjustment of RSS by variable numbers. RSS will decrease by more variables due to more fitting. The denominator factor will decrease as well. The division will be uncertain. if the decrease in RSS is more visible than RSE will decrease. 

Although the R^2 and RSE seems to be related, as the RSE contains variable numbers, it can give us extra information regarding the partial gain from adding a new variable. 
