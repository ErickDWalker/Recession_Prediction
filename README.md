# Recession_Prediction
This program will attempt to calculate a probability of recession 12 months in the future by training a model on past  macroeconomic data. The practical value of such a predictor is not limited to Federal Reserve officials attempting to set interest rate policy based on forecasted economic conditions. Another envisioned use is for portfolio managers, who might wish to shift weights of various asset classes in anticipation of a decline in economic activity. The independent variables being used to train the model are the yield curve, expressed as the difference between the 10-yr and 3-month yields on US Treasury securities, and the Civilian Unemployment Rate. All data used to build  the predictor is obtained from the Economic Database of the Federal Reserve Bank of St. Louis (FRED), while data on the S&P500 is taken from Yale Professor Robert Shiller's publically available database found here: http://www.econ.yale.edu/~shiller/data/ie_data.xls

*Data used to train the model begins March 1982 and ends December 2019. While the start of this period appears to conveniently 
coincide with the beginning of data availability for the yield spread, I believe it also is more representative of economic 
conditions going forward. Years prior to 1980 saw the rise of double digit inflation, among other major differences with today's 
macroeconomy, making it seem appropriate to limit the period studied to the more recent past. 
