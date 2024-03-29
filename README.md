# api_homework

### Instructions 
#### 1. Budget Analysis: Summarize the transaction data from the budget analysis and include images for each chart and table produced.

* Please find below Table 1 that shows the amount spent on each of the categories. 

Table 1 

| category          | amount        | 
| ----------------- |:-------------:| 
| Food and Drink    |  $3317.19     |
|  Payment          |    $6310.50   |
| Recreation        |    $235.50    |
| Shops             |  $1500.00     |
| Transfer          |   $20537.34   |
| Travel            |     $41.52    |


* Please find below pie chart. We can see that category that had the largest amount is Transfer, followed by Payment and followed by Food and Drink. the category with the least amount of spent was Travel with a value of $41.52 

![table](https://github.com/andreaovelar/api_homework/blob/master/pie_chart.PNG "Pie Chart")


* Please find below table 2 that shows the amount spent by months, please note that given that we only pull data from the last 90 days we are showing amounts spent from July to October. Also to note that for the month of October we only pull few days. 


Table 2 

| month          | amount        | 
| ----------------- |:-------------:| 
| 7(July)   |  $10645.24    |
| 8(August)          |    $10645.24   |
| 9(September)         |    $10645.24    |
| 10(October)            |  $6.33    |

* Please find below bar chart we can esily see that the spent per month is the same for July, August and September with a value of $10645.24 and the smallest value is for the month of October with an amount of $6.33

![table](https://github.com/andreaovelar/api_homework/blob/master/bar_chart.PNG "Bar Chart")

#### 2. Retirement Planning: Summarize the retirement portfolio analysis and include the charts for the Monte Carlo simulation.

Please find below figure that shows monte carlo similations for the portfolio of 60% Spy and 40% bonds for a period of 30 years 
![table](https://github.com/andreaovelar/api_homework/blob/master/monte_carlo.PNG "Monte Carlo")



Please find below figure that shows the distribution of ending returns for a period of 30 years 
![table](https://github.com/andreaovelar/api_homework/blob/master/distribution_ending_returns.PNG "Distribution Ending returns")

### Use the Monte Carlo simulation data to answer the following questions:

* What are the expected cumulative returns at 30 years for the 10th, 50th, and 90th percentiles?

| percentile          | value        | 
| ----------------- |:-------------:| 
| 10th percentile   |  1.289466    |
| 50th percentile           |    2.755764  |
| 90th percentile          |    4.824329 |

* Given an initial investment of $20,000, what is the expected return in dollars at the 10th, 50th, and 90th percentiles?

| percentile          | value        | 
| ----------------- |:-------------:| 
| 10th percentile   |  $25789.0   |
| 50th percentile           |    $55115.0  |
| 90th percentile          |    $96487.0 |

* Given the current projected annual income from the Plaid analysis, will a 4% withdrawal rate meet or exceed that value at the 10th percentile? Note: This is basically determining if retirement income is equivalent to current income.

Retirement portfolio does not meet the value at the the 10th percentile. the ending value would be 
1831 and is lower than the projected yearly income before tax (7389)

* How would a 50% increase in the initial investment amount affect the 4% retirement withdrawal? In other words, what happens if the initial investment had been bigger?

Retirement portfolio does not meet the value at the the 10th percentile. the ending value would be 
3617 and is lower than the projected yearly income before tax (7389)
