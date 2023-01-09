# Solution to AutosRUs’ production issue

## Introduction
AutosRUs’ is a car manufacturing company. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. Therefore, the data analytics team is going to review the production data for insights that may help the manufacturing team.

In this work, the data analytics team do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. 


## Part 1: Linear Regression to Predict MPG
### About Data
The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as __vehicle length, vehicle weight, spoiler angle, drivetrain__, and __ground clearance__, were collected for each vehicle. The first ten rows of the data set is shown below:

   <img width="616" alt="Screen Shot 2023-01-08 at 6 35 06 PM" src="https://user-images.githubusercontent.com/112113327/211224639-68716aff-65b2-4a07-a237-63440f158ba9.png">
  
### Multiple Linear regression on to predict MPG
The multiple linear regression equation was generated by considering the __mpg__ as the dependant variable and the __vehicle length, vehicle weight, spoiler angle, drivetrain__, and __ground clearance__ as independant variables. The results are shown below:

    
<img width="651" alt="Screen Shot 2023-01-08 at 10 56 33 PM" src="https://user-images.githubusercontent.com/112113327/211238953-8ea1b343-cc89-4146-85fd-0f7295fb875f.png">



