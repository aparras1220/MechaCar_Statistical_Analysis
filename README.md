# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
  * Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? Vehicle Weight, Spoiler Angle, AWD
  * Is the slope of the linear model considered to be zero? Why or why not? No, due to the P value coming back as lower than .05%.
  * Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? With our current model it does calculate at an approx 71% accuracy. There are additional factors we could look at to overall improve the model.

![image](https://user-images.githubusercontent.com/90172307/155949159-a2371242-256c-4015-8483-113fdc531c6b.png)


## Summary Statistics on Suspension Coils
  * The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? All lots but lot 3 meeting this variace. As show below the overall and lots 1 and 2 both have less than 100 variance but lot 3 has a variance of 170.

![image](https://user-images.githubusercontent.com/90172307/155949401-9f11d5ed-052d-4e3f-a3f8-a77ebefb7e56.png)

![image](https://user-images.githubusercontent.com/90172307/155949471-43eead84-2bde-48e4-9d39-b34083564b77.png)

## T-Tests on Suspension Coils
 Lot 1 and Lot 2 both have P-Value greater than our .05 therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar. Lot 3, on the other hand, has a value lower than our .05 so we can determine that there is a significant variance.
 
 ![image](https://user-images.githubusercontent.com/90172307/155954446-71ecf7ab-b009-441f-9e3e-517a446c91a7.png)

Lot 1:
 ![image](https://user-images.githubusercontent.com/90172307/155954503-1e79f4cb-7bfb-4fc2-8da2-72475f517030.png)

Lot 2:
![image](https://user-images.githubusercontent.com/90172307/155954562-611b6d02-91d0-4032-ba75-e53e16bd90ab.png)

Lot 3:
![image](https://user-images.githubusercontent.com/90172307/155954606-a491fd08-eadb-4dcb-aafb-f0badda78a5c.png)


## Study Design: MechaCar vs Competition
### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
   In your description, address the following questions: 
  * What metric or metrics are you going to test? With the current enconomy, consumers are looking much more at maintenance cost as well as fuel efficiency. 
  * What is the null hypothesis or alternative hypothesis? The Null Hypothesis would be .05 the common, meaning that there is no difference between other competitors.
  * What statistical test would you use to test the hypothesis? And why? Since we would be comparing to competitors a good one to use would be the Two-sample test and compares to each competitor individually. 
  * What data is needed to run the statistical test? We would need data on competitor vehicles in the fields on fuel efficiency and maintenance costs.


