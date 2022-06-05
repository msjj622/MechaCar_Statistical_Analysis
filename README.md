# MechaCar_Statistical_Analysis
AutosRUs an automotive manufacturing company is suffering from production troubles from their newest prototype, the MechaCar. Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team about the following list below.

• Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
• Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
• Run t-tests to determine if the manufacturing lots are statistically different from the mean population
• Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Deliverable 1
## Linear Regression to Predict MPG
![Deliverable_1](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/deliv_1_script.png)
![output_1](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/Linear%20Regression%20to%20Predict%20MPG.png)

- Imported The MechaCar_mpg.csv file and read into a dataframe
- Performed on all six variables in a linear regression mode
- Created statistical summary of the linear regression model with the intended p-values

Based on the anlysis, the six variablles impact on miles per gallon (mpg).
The p-Value(5.35e-11) tells that is sufficient evidence to reject null hypothesis. The slope of the linear model is not zero. The linear model predicts 68% since R-squared value is 0.6825.

# Deliverable 2
## Summary Statistics on Suspension Coils, 
![Deliverable_2](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/deliv_2_script.png)
![output_1](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/df_total_summary.png)
![output_2](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/df_lot_summary.png)

- Imported The Suspension_Coil.csv file and read into a dataframe
- Create a total summary dataframe that has the mean, median, variance, and standard deviation of the PSI for all manufacturing lots
- create a lot summary dataframe that has the mean, median, variance, and standard deviation for each manufacturing lot

The analysis shows that allowable PSI does not exceed 100 pounds as you can see the result of 62.29356 pounds PSI following the output_1 image. But, as you can see the output_2, Lot 3 is over 100 PSI which tells it required to be reviewd.

# Deliverable 3
## T-Tests on Suspension Coils 
![Deliverable_3](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/deliv_3_script.png)
![test_1]((https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/test_1.png)
![test_2](https://github.com/msjj622/MechaCar_Statistical_Analysis/blob/main/results/test_2.png)

- Compared all manufacturing lots against mean PSI of the population
- Compared each manufacturing lot against mean PSI of the population 

The first test according to test_1 image, p-value is 0.06 which is failed.
lot 1 with p-value is 1 is failed which means sample are the same from the population mean.
lot 2 with p-value is 0.6 is failed which means sample are the same from the population mean.
lot 3 with p-value is 0.04 is failed which means sample are different from the population mean.

# Deliverable 4
## Study Design: MechaCar vs Competition

In my perspective, the metrics of car price, maintenance cost and fule efficiency would be added to quantify comparing to other vehicles from other manufactueres. Null Hypothesis, MechaCar is reliable car compare to competition and Hypothesis, MechaCar is less reliable car compare to competition. A linear regression data would be used for maintenance cost and fule efficiency.


