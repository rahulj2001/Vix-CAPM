Exercise 1. VIX.  Using the attached data:
Estimate an AR(1) time series model of the VIX using data from 1990-2015.
For each day in the data, use your model to calculate a 21-trading-day-ahead forecast of the VIX.  What is the R-squared of the realized VIX on your forecast value in sample (over 1990-2015)?  What about out-of-sample (2016-most recent data)?
Plot the out-of-sample realized values (y) against predicted values (x) in a scatterplot.  Include both a 45-degree line and the best-fit line.  Write a paragraph summarizing your observations and how you might improve the model.
 
Exercise 2. Portfolios. Go to Yahoo Finance and download historical monthly stock price data for Microsoft (MSFT), Proctor and Gamble (PG), and the S&P 500 (^GSPC) from Jan 1 2010 onwards.
Calculate a series of returns (1+Return(t) = AdjClose(t) / AdjClose(t-1)).  What are the mean and standard deviation of returns for each symbol?  What are the estimated full-sample CAPM betas (and their standard errors) of MSFT and PG?
Calculate the returns to a portfolio of MSFT and PG that rebalances to 50%/50% weights at the start of January.  (The portfolio should rebalance only once per year.) What are the mean and standard deviation of returns of this portfolio?  What is the estimated CAPM beta and its standard error?
Plot the cumulative returns for all four investments through time and write a paragraph summarizing your observations.  Your plot should feature the y-axis on a log scale.  Make a table describing the statistics we have asked you to compute.  How does your results in (2) compare to (1)?  What, if anything, about this exercise should be improved?
