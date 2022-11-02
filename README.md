# MechaCar_Statistical_Analysis

## Overview
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

### Resources
- RStudio
- MechaCar_mpg.csv
- Suspension_Coil.csv

## Linear Regression to Predict MPG
  
  
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?  
![image](https://user-images.githubusercontent.com/86776606/199379364-ce980b3c-405a-4348-95c6-164ddd99515d.png)  
  P-values show intecept, and AWD are <0.05 which means these variables provide a non-random amount of variance.

  
- Is the slope of the linear model considered to be zero? Why or why not?  


- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  
![image](https://user-images.githubusercontent.com/86776606/199379466-1ba92734-89ff-4b35-8ca1-8262be30593b.png)  

## Summary Statistics on Suspension Coils

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?  
  
  ![lot_summary](https://user-images.githubusercontent.com/86776606/199372879-e093eee5-9a34-4e21-9f71-0fdadbb74657.png) 
  
  ![total_summary](https://user-images.githubusercontent.com/86776606/199372912-445b3962-070c-4be8-a113-893b21bf13aa.png)
  
Based on the data above, the variance column shows Lot1 and Lot2 do not exceed 100 pounds per square inch but Lot3 far exceeds the 100 pound limit. The total summary gives us a variance of 62.29 which means in total, the suspension coils do not exceed 100 pounds.
  

## T-Tests on Suspension Coils



## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?
