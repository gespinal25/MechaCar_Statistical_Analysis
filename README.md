# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
![D1](https://user-images.githubusercontent.com/95927043/165006930-fef7ddd4-e479-4dda-bcac-700e419d662d.png)

The variables/coefficients provided a non-random amount of variance to the mpg values in the dataset are vehicle weight, spoiler angle, and AWD.


#### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because the p-value is less of 0.05.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model predict mpg of MechaCar prototypes effectively because of the R^2 value of 71%. 

## Summary Statistics on Suspension Coils
### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The current maufacturing data meet this design specification for all manufactoring lot except Lot3. For Lot1 and Lot2 it meet the requirements because the variance of the suspension coil did not exceed 100 pounds per square inch (Lot1 = 0.9795918, Lot2 = 7.4693878). While Lot3 variance is 170.2861224.

## T-Tests on Suspension Coils
### Briefly summarize your interpretation and findings for the t-test results.
My interpretation and findings of the t-test results has shown me that all three lots have a p-value equal or less than one and each lot have a 95 percent confidence interval.
