# MechaCar Statistical Analysis
#### 26 Sept 2021

## Objective
The purpose of this project was to utilize R in an effort to draw a comparison of MechaCar vechicles against other industry standards. This was achieved through the use of linear regression models, t-tests and the creation of summary statistic tables.  

## Linear Regression to Predict RPG
For this portion of the analysis, several metrics including ground clearance, vehicle length, vehicle weight, spoiler angle, drivetrain were utilized in a linear regression model to predict the RPG of MechaCars. 
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - The variables that provided a non-random amount of variance to the mpg values were ground clearance and vehicle length. Additionally, vehicle weight provided a small amount of non-random variance, though not to the same degree of significance. 
- Is the slope of the linear model considered to be zero? Why or why not?
  - The linear model has a negative slope, and is therefore non zero. 
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - Given that the R squared value was .71, the likelihood that the model will predict the mpg of MechaCar prototypes effectively is 71%. Whether or not the industry standard requires a higher instance of probability for this simulation is key.

## Trip Analysis 

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- Lots 1 and 2 are both within the industry specifications, however, lot 3 is not. 

## T-Tests on Suspension Coils

## Hypothesis
