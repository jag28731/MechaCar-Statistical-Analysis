# MechaCar Statistical Analysis

## Overview of Project
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

### Purpose
In this challenge, I will help Jeremy and the data analytics team do the following:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

## Linear Regression to Predict MPG Summary
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - Vehicle_weight, spoiler_angle, and AWD provide a non-random amount of variance to the mpg values in the dataset.  
   
- Is the slope of the linear model considered to be zero? Why or why not?
  - The p-value is 5.35e-11, therefore the slope is not equal to zero.
   
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - The R-squared value is 0.7149, therefore approximately 71-72% of the predicitions will be correct using this linear model.  

![1](https://github.com/jag28731/MechaCar-Statistical-Analysis/blob/main/Resources/Linear%20Regression.PNG)

## Summary Statistics on Suspension Coils Summary
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The top chart indicates the mean, median, variance, and standard deviation totals. Lot 1 and 2 are similar to the total numbers however lot 3 exceeds in variance and standard deviation.
![2](https://github.com/jag28731/MechaCar-Statistical-Analysis/blob/main/Resources/Total%20Summary.PNG)
![3](https://github.com/jag28731/MechaCar-Statistical-Analysis/blob/main/Resources/Lot%20Summary.PNG)

## T-Tests on Suspension Coils Summary
- The p-value total result was 0.06028, which is above the average level of 0.05. All testing will not have the exact same value. 

## Study Design: MechaCar vs Competition
- What metric or metrics are you going to test?
  - The metrics to be tested will have to be numerical and have a pool of samples as not all values will be the same. 
   
- What is the null hypothesis or alternative hypothesis?
  - Null: MechaCar prototypes' costs are accurate because of all the enhanced features.
  - Alternate: MechaCar prototypes' costs are inaccurate because of all the enhanced features.
   
- What statistical test would you use to test the hypothesis? And why?
  - I would use summary statistics, for the most precise data for cost related inquries.
  
- What data is needed to run the statistical test?
  - All types of data are required, the more data, the more precise the tests can be to be compared to competitors.  

