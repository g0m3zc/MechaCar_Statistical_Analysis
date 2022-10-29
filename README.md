# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
The results of the Linear Regression are
- vehicle_length coefficent is 6.267e+00 with a probability of 2.60e-12 
- vehicle_weight coefficent is 1.245e-03 with a probability of 0.0776
- spoiler_angle coefficent is 6.877e-2 with a probability of 0.3069
- ground_clearence coefficent is 3.546e+0 with a probability of 5.21e-08
- AWD coefficient is 3.411e+00 with a probability of 0.1852

1. The variables/coefficients provided a non-random amount of variance to the mpg values in the dataset are
The variables that provided a non-random amount of variance are vehicle length, ground clearance and AWD.  This determination is based on the coefficients being not close to 0.

2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because they did have coefficients that were not close to zero.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, because the multiple R-squareed is .7149, this linear model could be used to predict prototypes effectively in their mpg.


## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The manufacturing lots do meet the design specification as their combined variance of suspension coils is 62 PSI.  However, the PSI of Lot3 is 170.  This exceeds the design specifications.  Lot1 and Lot2 do meet the requirement at 1 PSI and 7 PSI.


## T-Tests on Suspension Coils

Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
We will rely on the p-value for each test to determine if the results are above significance level.  Our null hypothesis is that there is not a difference from the lots from the population mean.  We can set our threshold at 5%.

T test for all manufacturing lots
<img width="463" alt="One Sample T Test" src="https://user-images.githubusercontent.com/106936638/198849079-5f2efd94-2b18-43c6-9219-0cc396b4bf3b.PNG">
The P value is .06.  Based on this we would reject the null hypothesis.  There is a difference in the lots in PSI from the population mean.

T test for Lot1
<img width="448" alt="Lot1" src="https://user-images.githubusercontent.com/106936638/198849161-03d82728-69ea-44ee-bf58-9c9bbd492a8b.PNG">
The P value is 1.  We would reject the null hypothesis.

T test for Lot2
<img width="454" alt="Lot2" src="https://user-images.githubusercontent.com/106936638/198849165-5462ba64-f1ae-4932-bdc8-103a3204e90c.PNG">
The P value is .6.  We would reject the null hypothesis.

T test for Lot3
<img width="449" alt="Lot3" src="https://user-images.githubusercontent.com/106936638/198849168-e274cb41-6ac2-4e1c-afd7-970b8deef108.PNG">
The P value is .04.  We would fail to reject the null hypothesis.


## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
