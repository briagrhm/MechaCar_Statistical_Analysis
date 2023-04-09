# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="509" alt="Screenshot 2023-04-09 at 8 01 42 AM" src="https://user-images.githubusercontent.com/120140614/230771316-c7e90397-06a6-40be-afdf-bd94f1101187.png">

1.Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provided a non-random amount of variance to the mpg values are the vehicle length and the ground clearance. This is based on the p-values being lower than the expected .05. So these variables will have a significant effect on the mpg. 

2.Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not zero. The p-value os 5.35e-11. This is significantly lower than 0.05. This rejects the null hypothesis that the linear model is zero or has no effect. 

3.Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, this linear model does predict the mpg. The r-squared is 0.7149, so about 71% of the mpg predictions will be determined by this model. 


## Summary Statistics on Suspension Coils
<img width="489" alt="Screenshot 2023-04-09 at 8 22 35 AM" src="https://user-images.githubusercontent.com/120140614/230772249-c6ed88ac-b5fb-477d-8c92-8c3de1843970.png">
<img width="634" alt="Screenshot 2023-04-09 at 8 22 05 AM" src="https://user-images.githubusercontent.com/120140614/230772251-12b2cf50-461a-49ea-847d-0f51e6731f09.png">
Based on the total_summary chart the variance PSI which is at 62.29, is withing the 100 pounds per square inch limit. So the manufacturing data does meet the specification requirements. However, when looking at the lots individually. Lots 1 and 2 fall within the manufacturing specifications with variances at 0.97 and 7.46. Lot 3 however is beyond the 100 PSI sprcification, the variance is 170.28, lot 3 is causing alot of variance. WHich may be making the total_summary variance higher. 

## T-Tests on Suspension Coils
Summary of t-test results across all lots 

<img width="456" alt="Screenshot 2023-04-09 at 8 37 15 AM" src="https://user-images.githubusercontent.com/120140614/230772907-bde22997-ccf4-4f6b-bcb6-869be03047f7.png">

The summary of all manufacturing lots show that the mean is 1498.78. The p-value is 0.06 which is higher than the 0.05 common significance level. This means we cannot reject our null hypothesis. The mean of the manufacturing lots are statistically similar to population mean of 1500.

Individual lot t-test 

<img width="446" alt="Screenshot 2023-04-09 at 8 38 20 AM" src="https://user-images.githubusercontent.com/120140614/230773179-3000aa4d-6c41-4aaa-8e76-ffa7ed18392c.png">


<img width="438" alt="Screenshot 2023-04-09 at 8 38 34 AM" src="https://user-images.githubusercontent.com/120140614/230773185-c4fd4b9f-08e9-4fda-b52b-3060a2d63e32.png">

<img width="434" alt="Screenshot 2023-04-09 at 8 38 47 AM" src="https://user-images.githubusercontent.com/120140614/230773189-97b54062-7491-4e33-ba30-012bd408a640.png">

Fot the individual lots t-test lots 1 and 2 have p-values higher than the .05 significance level, they are 1 abd 0.06 respectively. The means are 1500 and 1500.2 For these two lots we can not reject our null hypothesis that their is no significanct difference between the sample mean and the presumed population mean, ebenthough they are at 1500. 
Lot 3 has a p-value of 0.04 which is below the 0.05 significance level and has a mean of 1496.14. Because of the p-value we can reject our null hypothesis that there is no statistical difference between the sampl mean and the presumed mean of 1500. 

## Study Design: MechaCar vs Competition
3 year collection of Tire maintenacne required by each vehicle after set amount of miles 7000 miles  
Independent variable: Tire Type
Dependent variable: Tire Maintenance Prices 
Independent: Mileage 
Dependent: Number of Maintenance visits 

Hypothesis: Null and Alternate 
Null Hypothesis: MechaCar requires less tire maintenance after 7000 when compared to the competitor 
Alternate Hypothesis: MechaCar does not require less tire maintenance after 7000 miles when compared to the competitor. 

Statistical test 
Line of linear regression would be the test to use and determine which cars over time required more maintenance as well as to determine, which car pays more in maintenance. 

The data needed to run this statistical test is the recording of the mileage for each car. The number of visits and the prices paid for the services. 







