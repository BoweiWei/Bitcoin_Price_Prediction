# Bitcoin Price Prediction
Analyze the Bitcoin price from 1.1.2012 to 10.31.2018 using timestamp and ARMA model to predict the following price in the next 8 months

1. Visualize and check data distribution
2. Clean the data, remove the useless columns like ID
3. Sort the dataset using time stamp
4. Calculate the mean price in different time base: Daily, Monthly, Quarterly and Yearly
5. Plot the graph for different time based dataset
6. Prepare the params range
7. Train the dataset using Monthly based dataset with each pair of params using ARMA model
8. Find the best params according to the lowest best_aic
9. Predict the next 8 months price using the best params in ARMA
10. Plot the difference between the predicted price and the real price for the whole time
11. Done all over again using the quarterly based data

Conclusion: ARMA model predicted that the Bitcoin price will be dropped to around $4000 dollar in 8 month. And it did a great job. The actual price dropped right below $4000. The monthly based dataset performed better than the quarterly since more details are produced. 

Here's the monthly graph:
![monthly](https://github.com/BoweiWei/Bitcoin_Price_Prediction/blob/master/Monthly.png)

Here's the quarterly graph:
![quarterly](https://github.com/BoweiWei/Bitcoin_Price_Prediction/blob/master/Quarterly.png)

