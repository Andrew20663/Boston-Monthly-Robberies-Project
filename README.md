# Boston-Monthly-Robberies-Project

My time series final project is based on monthly robberies that occurred in Boston during the
years of 1966 to 1975 and being able to forecast the number of robberies from June to October.
The main questions I wanted to address from this data set that would help me forecast were:


  1) Can I create a time series model that could accurately model this behavior?
  
  
  2) Can my model forecast a close estimate of the amount of robberies that would occur in the next five months?


Therefore, in order to conduct this model, I implemented the necessary steps to build my time
series model. In order to come up with this time series model, I obtained the data set and
removed the last five months to see if my model was valid. I then observed three different
transformations which were, Box Cox, log, and square root. After observing the trend and nonconstant
variance features on the graph of the Box-Coxed data, I differenced it. After, I came up
with a model of ARIMA(0,1,1) and tested the residuals for normality by conducting Box test,
Mcleod test, and Shapiro test. I obtained positive results from these tests and as a result I was
able to forecast the next five months. The key result I obtained was that my model indeed
followed an ARIMA(0,1,1) for both the transformed data and the original data because the
forecasted values were within the 95% confidence interval along with the actual data.
