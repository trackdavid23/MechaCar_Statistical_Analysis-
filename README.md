# MechaCar_Statistical_Analysis-

## Linear Regression to Predict MPG
![Screen Shot 2022-02-06 at 11 48 53 PM](https://user-images.githubusercontent.com/59430635/152726341-75142a47-5405-4bc7-93af-a0e2eee53c7c.png)

Designed a linear model in R that predicts the mpg of MechaCar prototypes using several variables from the MechaCar_mpg.csv file. Determined the p-value and the r-squared value for the linear regression model.

Linear Regression Model:


## T-Tests on Suspension Coils
Determine if the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch

![Screen Shot 2022-02-06 at 11 19 55 PM](https://user-images.githubusercontent.com/59430635/152726241-b8f68ffa-523b-466c-91dd-7e40d36180a6.png)

![Screen Shot 2022-02-06 at 11 19 44 PM](https://user-images.githubusercontent.com/59430635/152726252-4fb8aac3-6510-4fbb-a984-b79e79a5623e.png)

Summary:

Hypothesis:Perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

Null Hypothesis: There is no mean difference between mean PSI for (All, Lot 1, Lot 2, Lot 3) of MechCar and the benchmark of 1500 PSI.

Alternate Hypothesis: There is a difference between the mean PSI for (All, Lot 1, Lot 2, Lot 3) of MechCars and the benchmark PSI of 1500.

Alpha level at α = .05

All Manufacturing Lots: Because the p-value of 0.06028 is greater than .05, the null hypothesis is retained and the observed mean of 1498.78 is close enough to 1500 to conclude that there is no statistically significant difference between the two numbers - the PSI of all MechaCar and the benchmark level of 1500 PSI.

Individual Lots: For Lot1 the p-value is 1.0 and for Lot 2 the p-value is 0.0672, so therefore for these lots there is no statistical difference between the PSI of each lot and the benchmark of 1500 PSI; null hypotheses is retained. For Lot 3 the p-value is 0.04168, therefore there is a significant statistical difference between Lot 3 PSI and benchmark of 1500 PSI; null hypothesis is rejected.

## Study Design: MechaCar vs Competition
Design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

Hypothesis: If we compare the highway fuel efficiency of the improved Model A of MechaCar, it should perform at least 50% faster than those cars that did not get the improvement.

Null Hypothesis: If we don’t improve Model A MechaCar with this new feature X, then Model A Mechacar on average will not give better highway fuel efficiency than the competition car when driven on a higher than 70 miles per hour for 1 hour.

Alternate Hypothesis: If we improve Model A MechaCar with this new feature X, then Model A Mechacar on average will give better highway fuel efficiency than the competition car when driven on a higher than 70 miles per hour for 1 hour.

Data Needed: Would need to collect highway fuel efficiency data for manufacring lots as well as for the competition.

Statistical test to be perormed: Perform one sample t-test would be used to compare the mean of a sample to the population; In this case the mean of production sample which includes improved feature X of MechCar would be compared to the mean of fuel efficiency of a competition car.
