% Assignment 1: Forecasting / Financial Data -- Fundamental Concepts
% Andrew G. Dunn^1^
% ^1^andrew.g.dunn@u.northwestern.edu

\vfill

**Andrew G. Dunn, Northwestern University Predictive Analytics Program**

Prepared for PREDICT-413: Time Series Analysis and Forecasting.

Formatted using the \LaTeX\, references managed using pandoc-citeproc.

\newpage

# Part 1

Consider the daily simple returns of Netflix (NFLX) stock, Center for Research In Security Prices (CRSP) value-weighted index (VW), CRSP equal-weighted index (EW), and the S&P composite index (SP) from January 2, 2009 to December 31, 2013. Returns of the three indices include dividends. The data are within the file `d-nflx3dx0913.txt` and the columns show permno, date, nflx, vw, ew, and sp, respectively, with the last for columns showiing the simple returns.

## Part A

Computer the sample mean, standard deviation, skewness, excess kurtosis, minimum, and maximum of each simple return series.

## Part B

Transform the simple return to log returns. Compute the sample mean, standard deviation, skewness, excess kurtosis, minimum, and maximum of each log return series.

## Part C

Test the null hypothesis that the mean of the log returns of NFLX stock is zero.

## Part D

Obtain the empirical density plot of the daily log returns of Netflix stock and the S&P composite index.

# Part 2

Consider the monthly log returns of General Electric (GE) stock from January 1981 to December 2013. The original data are monthly returns for GE stock, CRSP value-weighted index (VW), CRSP equal-weighted index (EW), and S&P composite index (SP) from January 1981 to December 2013. The returns include dividend distributions. The data are within the file `m-ge3dx8113.txt` and the columns show permno, date, ge, vwretd, ewretd, and sprtrn, respectively. Perform tests and draw conclusions using the 5% significance level.

## Part A

Construct a 95% confidence interval for the monthly log returns of GR stock.

## Part B

Test $H_0 : m_3 = 0$ versus $H_a : m_3 != 0$, where $m_3$ denotes the skewness of the return.

## Part C

Test $H_0 : K = 3$ versus $H_a : K != 3$, where $K$ denotes the kurtosis.

# Part 3

For this, ues the monthly Australian short-term overseas visitors data from May 1985 to April 2005 from `Forecasting: principles and practice` the Hyndeman and Athana­sopou­los text.

# Part A

Make a time plot of your data and describe the main features of the series.

# Part B

Forecast the next two years using Holt-Winters' multiplicative method.

# Part C

Why is multiplicative seasonality necessary here?

# Part D

Experiment with making the trend exponential and/or damped.

# Part E

Compare the RMSE of the one-step forecasts from the various methods. Which is preferred?

# Part F

Fit each of the following models to the same data, examine the residual diagnostics and compare the forecasts for the next two years:

    Multiplicative Holt-Winters' Method

    ETS models

    Additive ETS model applied to a Box-Cox transformed Series

    Seasonal naive method applied to the Box-Cox transformed series

    STL decomposition applied to the Box-Cox transformed data

    ETS model applied to the seasonally adjusted (transformed) data

# Part G

Which model from above do you prefer
