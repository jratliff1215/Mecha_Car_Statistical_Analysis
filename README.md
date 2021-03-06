# MechaCar Statistical Analysis

*All figures are located in the Appendix below the ReadMe*

## Linear Regression to Predict MPG (Figure 1)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Our vehicle weight, spoiler angle, and AWD produced a non-random variance and indicate these variables have a significant impact on the MPG value. Ground clearance and vehicle length have the largest random variance impacting the MPG.  

- Is the slope of the linear model considered to be zero? Why or why not?

The p-value is 5.35e-11, less than the alpha value of 0.05. This suggests the slope is a non-zero value. The predictor variable is associated with changes in the response variable.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-squared value predicts the effectiveness of our model with a range of 0.0 to 1.0. Based on the dataset, the R-squared value is 0.7149, which can predict the mpg of MechaCar protypes effectively. 


## Summary Statistics on Suspension Coils 
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 

-Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

For all manufacturing lots in total (Figure 2) , the variance does not exceed 100 pounds per square inch. The summary statistics show the Variance is 62.29 for all manufacturing lots in total. Thus, design specs are met for the data set.

## Lot Summary (Figure 3)
Lot 1 has a variance of 1.0 and lot 2 has a variance of 7.5. Lot 3 does not meet coil variance expectations, their variance is 170.2 which exceeds the 100 pounds variance limit.

## T-Tests on Suspension Coils (Figure 7)

- Summary of interpretation and findings for the t-test results

Lot 1 and 2 have a variance that does not exceed 100 pounds per square inch (Figures 4 and 5, respectively). Specifically, Lot 1 has a variance of 1.0 while lot 2 has a variance of 7.5. Also, Lot 3 does not meet coil variance expectations, their variance is 170.2 which exceeds the 100 pounds variance limit (Figure 6).

# Study Design: MechaCar vs Competition
One feature that people are interested in when buying a car is how much horsepower the car has and off the line capability. Horsepower, mpg and engine block size  are 3 factors that may go into consumer decision making. We can use our tests to see if our MechaCar is much different from the competition. We can make a null hypothesis stating that it is not different from the competition and our alternative would be the opposite. To do this we will need to use our t-test after collecting data from different types of competitor vehicles. Our t-test will be comparing the population of all types of competitor vehicles.


# Appendix
**Figure 1 - Linear Regression to Predict MPG**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/mpg_linear_regression.PNG" width="600" height="350"> 


**Figure 2 - Total Set Summary**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/total_summary.PNG" width="350" height="75"> 


**Figure 3 - Lot Summary**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/lot_summary.PNG" width="500" height="100"> 


**Figure 4 - Lot One T Test**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/lot_one_ttest.PNG" width="600" height="280"> 


**Figure 5 - Lot Two T Test**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/lot_two_ttest.PNG" width="600" height="280"> 


**Figure 6 - Lot Three T Test**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/lot_three_ttest.PNG" width="600" height="280"> 


**Figure 7 - All Lot T Test**

<img src="https://github.com/jratliff1215/Mecha_Car_Statistical_Analysis/blob/main/Challenge/images/all_lots_ttest.PNG" width="600" height="280"> 

