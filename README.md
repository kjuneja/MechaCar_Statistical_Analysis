# MechaCar_Statistical_Analysis

## Overview of Project

## Purpose
The purpose of this project is to help Jeremy and the data analytics team do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

This project consists of three technical analysis deliverables and a proposal for further statistical study. We’ll submit the following:

* Deliverable 1: Linear Regression to Predict MPG
* Deliverable 2: Summary Statistics on Suspension Coils
* Deliverable 3: T-Test on Suspension Coils
* Deliverable 4: Design a Study Comparing the MechaCar to the Competition

### Linear Regression to Predict MPG

![MechaCar](https://user-images.githubusercontent.com/25447945/143790437-e9e2a147-f01f-42cb-bf27-7922d5876642.png)

Using the result above we will answer the following questions:

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
   - The variance of non-random variable is usually 0. The Intercept, vehicle_length, and ground_clearance coefficients provide a non-random variance to the mpg values.
2. Is the slope of the linear model considered to be zero? Why or why not?
   - The slope of the linear model is not considered 0 because of the extremely small p-value. 
3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
   - Yes the linear model predict mpg of MechaCar prototype effectively as the adjusted R-square value is 0.6825.
 
### Summary Statistics on Suspension Coil

![Suspension](https://user-images.githubusercontent.com/25447945/143790439-c0885cdd-5ea5-472b-a027-24a1a408b47b.png)

![Lot_Summary](https://user-images.githubusercontent.com/25447945/143790435-7001c474-ba74-4967-9ec1-811854d717ea.png)

Using the above result we can answer the following questions:

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - Yes the current manufacturing data meet the design specification for all manufacturing lots in total , howver it does not meet the specification for each lot individually as the third lot demonstrates a much higher variance. 

### T-Test on Suspension Coils

#### T-Test on Entire Lot

![T-Test](https://user-images.githubusercontent.com/25447945/143790441-8927bda9-1329-4c91-9aad-185068f8c9fb.png)

#### T-Test on individual lots 

![Lot_T-Test](https://user-images.githubusercontent.com/25447945/143790436-fa9773d9-98a7-4609-961a-7257614884eb.png)

### Study Design: MechaCar vs Competition

We can have another statistical study to determine MechaCar's standing againsts the competition. We can have linear regression on city and highway fuel efficiency. Gas prices are rising day by day and we can study the gas prices to make the model much more effective to understand the trends and this feature would be very helpful to the consumers buying new cars

The following metrics can be included in the study:
1. City and Highway fuel efficiency 
2. Horse Power
3. Vehicle MPG
4. Vehicle AWD
5. Vehicle Weight

Null Hypothesis: The mean fuel efficienty of most vehicle is 
 - City: 28
 - Highway: 35

To test the null hypothesis we will find the mean of all vehicle fuel effiency provided to us

We would need all the data of most popular vehicle that has the above metrics.

