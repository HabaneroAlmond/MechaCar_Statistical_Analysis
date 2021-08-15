# Analyzing production data of AutosRUs 'MechaCar'
AutoRUs' new prototype 'MechaCar' is suffering from production issues and the management tasked our data analytics team with reviewing their production data. To help AutoRUs' our team:
  -performed multiple linear regression analysis to identify which parts of our production data can help predict the MPG of the prototype.
  -collected summary statistics on the PSI of the suspension coils
  -used t tests to find out if the manufacturing lots are statistically different from the mean population
  -designed a statistical study to compare the MechaCar to vehicles from other car companies
  
# Linear Regression to Predict MPG
![deliverable1code](https://user-images.githubusercontent.com/82848585/129486496-6252a838-2858-4ff4-b69c-82043d9be6d3.png)

![linearregMPG](https://user-images.githubusercontent.com/82848585/129486632-09484058-af37-4958-8b6e-ad5ee6b86162.png)

  -Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? For our linear regression results the intercept, vehicle length and ground clearance provided a non-random amount of variance to the mpg values. The intercept being significant (0.001) shows us that there are other factors that weren't available in our data set that could contribute to the mpg aside from just the vehicle length and ground clearance.
  
  -Is the slope of the linear model considered to be zero? Why or why not? No, because the vehicle length and ground clearance (independant variables) have a statistically significant relationship to the mpg (dependant variable).
  
  -Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  Somewhat effectively. The r-squared value is 0.71 meaning that around 71% of all our mpg predictions with be correct, while the p-value of our linear regression model is 5.35e-11, much smaller than our required significance level of 0.05. This gives us enough evidence to reject our null hypothesis. 


# Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? 

![deliverable2code](https://user-images.githubusercontent.com/82848585/129486754-6049f771-9d62-47a4-8b6f-5b25008846e7.png)
![PSI](https://user-images.githubusercontent.com/82848585/129486756-43daadcf-c85d-4a89-9664-0c4213ded1e1.png)
![manufacturinglotPSI](https://user-images.githubusercontent.com/82848585/129486759-986afffd-33a5-4a63-900f-a8049a4e9724.png)

With our results we found that the lots when grouped meet the design specifications with a PSI variance of 76. Only lots 1 and 2 meet the design specs with a PSI variance of 1 and 10, lot 3 has a PSI variance of 220 which does not meet the AutoRUs' design specs.

# T-Tests on Suspension Coils
For our analysis we perfomed t tests to find out if our manufacturing and individual lots were different from the population mean of 1500 PSI. 
  -Null Hypothesis: There is no significant difference between the average PSi of the manufacturing/individual lots and the population mean of 1500 PSI
  -Alternate Hypothesis: There is a significant difference between the average PSI of the lots and the popualtion mean.
The results of our t-test analysis showed that the p-value average across all lots is about .6 which is outside our significance level of .05. Since the p-value is more than our significance valye we do not reject the null hypothesis. 

![deliverable3code](https://user-images.githubusercontent.com/82848585/129486811-43c88c56-777d-40d6-b2b3-a50850739971.png)
![ttest](https://user-images.githubusercontent.com/82848585/129486865-1f16a47f-a7fd-4a5f-9890-ab7b2e7b57b4.png)
![ttests1-3](https://user-images.githubusercontent.com/82848585/129486973-2f279439-72e4-4262-94e6-f23a5380398e.png)



# Study Design: MechaCar vs Competition.


