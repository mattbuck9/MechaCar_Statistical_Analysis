# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
### ![image](https://user-images.githubusercontent.com/111928259/215292918-a1db4d21-9648-4939-ab39-56d430f94538.png)

### As you can see from the screenshot, the variables that provided a non-random amount of variance to the mpg values were Vehicle Length, Vehicle Weight, Spoiler Angle, Ground Clearance, and whether or not the vehicle had All Wheel Drive. 
### The slope of the linear model is not considered to be zero, as the P-Value for the F-statistic is less than 0.05. This shows a significant relationship between the predictor variables and the response variable. 
### Yes, the linear model does predict the MPG of MechaCar prototypes. The R-squared value of 0.7149 shows that the variance in mpg values is explained by the predictor variables based on the model. 

## Summary Statistics on Suspension Coils
### Here is the data from total_summary
### ![image](https://user-images.githubusercontent.com/111928259/215294062-9c8aef85-34e5-4830-9c05-6e9c5139d33d.png)

### And here is the data from lot_summary
### ![image](https://user-images.githubusercontent.com/111928259/215294081-4db2f13a-7a73-4e67-8251-9e445e9789b9.png)

### For the lots in total, the manufacturing data does appear to meet the design specification that the variance of the suspension coils must not exceed 100 pounds per square inch. However, if you look at the lot_summary data, it shows that Lot3 does not meet the design specification. This means that Lot1 & Lot2 follow the design specifications, as well as the overall total, but not for Lot3.

## T-Tests on Suspension Coils
### Here are the results of the T-Test of all lots together
### ![image](https://user-images.githubusercontent.com/111928259/215294280-caf82f55-74be-4532-84ac-345d4405e7c6.png)

### Here are the results of the T-Test for Lot1
### ![image](https://user-images.githubusercontent.com/111928259/215294299-10acce14-dae0-41ec-9244-06047e53e7d6.png)

### Here are the results of the T-Test for Lot2
### ![image](https://user-images.githubusercontent.com/111928259/215294311-d00cf3ae-4e1b-4b99-8591-80e2176821ea.png)

### Here are the results of the T-Test for Lot3
### ![image](https://user-images.githubusercontent.com/111928259/215294330-2c6da552-357c-4417-aff0-7be4a3fc3485.png)

### The results showed that Lot1 and Lot2 have very close T-Test values to 1500, whereas Lot3 has the highest T-Test variance, at 1496.14.

## Study Design: MechaCar vs Competition
### A statistical study to quantify how the MechaCar performs against competition would require some thoughts as to what potential buyers would want to use to compare cars. Thinking back to my own experiences buying a car, I would want to know the mileage, the price, safety ratings, stuff like that. I would test the fuel efficiency, safety rating, and cost. The null hypothesis would be that there is no statistically significancy between the fuel efficiency, safety rating, and cost of competitors compared to MechaCar. The alternative hypothesis is that there will be a significant difference in the these metrics between MechaCar and Competition. I would use a two-sample t0test to compare two groups (MechaCar & Competition) on the identified metrics (fuel efficiency, safety rating, and cost). To run that test, I would need the data from both the competitors and MechaCar. 
