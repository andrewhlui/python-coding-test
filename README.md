# python-coding-test
Note: all screenshots are in 'Issues'.

Requirements
I wrote this using Spyder with Anaconda (Python 2.7). You will need to be able to import the following modules:
bokeh, 
pandas,
statsmodel.api

Instructions:
1. Enter code in Python
2. Run Python
3. Give .csv file location
4. Look at .html files. They should open automatically, if not, they'll be in the same folder as the Python program. 

Reasoning for model:
For the regression, I lagged the Airpassengers variable twice to deal with autocorrelation and logged the AirPassengers variable because the residuals didn't have constant variance. Residuals don't show any (major) problems now. 
There was a small improvement between using two lag variables; I decided to include the second one because it was still statistically significant. 



