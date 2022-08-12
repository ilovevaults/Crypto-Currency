# Crypto-Currency
## Goal
The goal was to create a report for an investment bank which was interested in offering a new cryptocurrency investment portfolio. The report in the analysis shows cryptocurrencies that are on the trading market and how they could be grouped by a classification system for this new investment. In order to complete this analysis, I am performing unsupervised machine learning functions on data provided by CryptoCompare. The data used was a list of cryptocurrencies that were available for trading on the market.
## Results  
I started out by cleaning the data that was provided and the result were cryptocurrencies that are currently trading, have a defined algorithm, and a complete data set. 
I was left with 532 different types after the data was cleaned. Below is a 3d scatter plot of three different groups of cryptocurrencies that are grouped together 
![3D Scatter Plot](https://user-images.githubusercontent.com/98357581/176793619-c60cb67a-b965-4de2-869f-2278ed28c8b0.png)
The next 2d scatter plot shows the relationship between total coin supply and the number of coins mined.
![bokeh_plot](https://user-images.githubusercontent.com/98357581/176793725-e409c5d7-b4cc-4981-b62f-e58250bc6e2c.png)
### Summary
From the first graph there are four different groups and two of them are closely clumped together. Most currencies fall under these two groups. One group is further away from the rest of the groups and then the last group only has one type. These outliers could exist because they are either overperforming or underperforming but more analysis has to be done to determine whether or not this is true.
The second graph shows most data points are scattered between 0% to 40%. The group with the least amount of data points are very close to 0% while the group with just one data point or currency is very close to 100%
