# Oden_tech
Generalized Approach

1)	Use dummy data representative of a time series. Data used in my case is listed below.
https://datamarket.com/data/set/22t8/monthly-number-of-employed-persons-in-australia-thousands-feb-1978-apr-1991#!ds=22t8&display=line
(Monthly number of employed persons in Australia: thousands. Feb 1978 – Apr 1991)
Note: Only first 54 lines of data was used, and values were deleted at random to better mirror a time series with missing  or unusable values.
2)	Datetime Indexing – Made dataframe fit for time series operations
3)	Asking user to input forecast horizon
4)	Data Exploration & Accounting for missing values
5)	Time Series Decomposition
6)	Model Selection
a.	Holt-Winters – additive	
b.	Holt-Winters – multiplicative 
c.	SARIMAX
i.	Grid Search for optimum hyperparameters
7)	All models were evaluated using their respective AIC values
8)	Displaying results for the 3 models used

Assumption: Time Series has some seasonality to it

