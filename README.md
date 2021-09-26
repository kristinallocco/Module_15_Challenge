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
This portion of the analysis assessed whether or not the suspension coils met menufacturing standards. 
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - Lots 1 and 2 are both within the industry specifications, however, lot 3 is not. 
  
 <img width="450" alt="Lot Summary" src="https://user-images.githubusercontent.com/85713470/134826884-745cb42a-f9d5-4a4f-a5e4-2b360523e914.png">

## T-Tests on Suspension Coils
T-tests to were utilized in order to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. 


#### All lots
<img width="450" alt="AllLots" src="https://user-images.githubusercontent.com/85713470/134826807-a771175b-6861-4562-95c2-1d923bd47019.png">

#### Lot 1
<img width="450" alt="Lot1ttest" src="https://user-images.githubusercontent.com/85713470/134826815-71a966ef-bdc0-4064-a843-187e3d43d4a0.png">

#### Lot 2
<img width="450" alt="lot2ttest" src="https://user-images.githubusercontent.com/85713470/134826819-b1894e54-a059-43db-ad6c-dd235c9f0c52.png">

#### Lot 3
<img width="450" alt="lot3 ttest" src="https://user-images.githubusercontent.com/85713470/134826822-07ef342c-e875-4240-88be-443a950a48dd.png">

## Hypothesis
