# This strategy is for educational purposes only, 
 its a good baseline to further develop as it incorporates several input sources such as tickr to make trading decisions.  
 
(This strategy is not profitible yet !);   

This strategy is for crypto trading and works with Hummingbot, It was set up to run on my raspberry pi, feel free to build upon it to try and make it profitible. 

The strategy was initially developed for pure market making, since then i have expanded it to trade with other methods and additional signals. 
It automatically fetches recent prices (candles) and correlates proven statistical patterns to influence trade parameters and adjusts on the fly given the volotility of the market and each coin. 
It trades 5 different coins at the same time, and depending on your machine you can easily add or remove coins. 
The current Tickr implementation is more so a proof of concept as it only uses a few patterns right now.


Credit to "https://github.com/syncsoftco/tickr" As it Fetches Candles with Tickr. 

