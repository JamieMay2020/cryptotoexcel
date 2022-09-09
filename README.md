# cryptotoexcel
This project used binances python client. 
It takes the 50 most popular coins by market cap, and gets their historical/current price from binances client.
It then sorts the data and finds the price from, now, 2hrs ago, 24hrs ago and then finally 1 month ago.
It finds the percentage change between the price between the different time frames and now.
Then it ranks the coins amongst themselves, for each time frame, from the percentile.
Then as this is a momentum investing strategy, it takes the average of the percentile from time frames and outputs a high quality momentum score. 'HQM'

Then with this data thats in a pandas table, it takes it and puts it into a csv using xlsxwriter.

