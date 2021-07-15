# Bitcoin_Market_Chart

This market chart was created to pull the historical data for Bitcoin over the last 30 days. I first used Python to pull the data from the CoinGecko API by creating a function 
that can be reused for other types of API calls.

Next, I separated the data into 3 dataframes (one each for prices, market caps, and total volume).

I then changed the unix date stamp in the prices dataframe to a readable date, and dropped the date columns from the other dataframes.

I used pd.concat to combine the dataframes and create a new dataframe with my desired data.

Finally, I created a plotly graph to show the correlation between price and volum on any given date over the 30-day period.
