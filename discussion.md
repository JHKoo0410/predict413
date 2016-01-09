discussion
==========

# Week 1: Forecasting / Financial Data -- Fundamental Concepts

## Which of the following distributions are appropriate for modeling financial returns:  normal, lognormal, stable, scale mixture of normals?  Describe why or why not they are appropriate.

The statistical distribution of asset returns plays a central role in financial modeling. Assumptions on the behavior of market prices are necessary to test asset pricing theories, to build optimal portfolios by computing risk/return efficient frontiers, to value derivatives and define the hedging strategy over time, and to measure and manage financial risks [^0]. However, neither economic theory nor statistical theory exist to assess the exact distribution of returns. Distributions used in empirical and theoretical research are always the result of an assumption or estimation using data [^0].

A traditional assumption made in financial study is that the simple returns are independently and identically distributed (iid) as normal with fixed mean
and variance [^1]. This modeling approach is used extensively in Modern Portfolio Theory (MPT)[^2]. In reality, it is frequently observed that returns in equity and other markets are not normally distributed. Large swings (3 to 6 standard deviations from the mean) occur in the market far more frequently than the normal distribution assumption would predict [^3].

When returns fall outside of a normal distribution, the distribution exhibits skewness or kurtosis. Skewness is known as the third "moment" [^4] of a return distribution and kurtosis is known as the fourth moment of the return distribution, with the mean and the variance being the first and second moments, respectively. Skewness and kurtosis are important because in reality few investment returns are normally distributed. It is common to predict future returns based on standard deviation, but that prediction assume a normal distribution as a model. Skewness and kurtoses measure how a measured distribution differs from a normal distribution, and as such provide an indication of the reliability of predictions based on standard deviation of a normal model [^5].

Acknowledging that few returns are normally distributed, it's possible to examine other models of distribution. For example, by transforming returns to log returns one could use a log-normal distribution. However, the log-normal assumption is not consistent with all the properties of historical stock returns. In particular, many stock returns exhibit a positive excess
kurtosis [^1].

Stable distributions are capable of capturing excess kurtosis shown by historical stock returns. However, non-normal stable distributions do not have a finite variance, which is in conflict with most finance theories. In addition, statistical modeling using non-normal stable distributions is difficult [^1].

One can further use transformations and a scale mixture or finite mixture of normal distributions to model returns.  Advantages of mixtures of normal include that they maintain the tractability of normal, have finite higher order moments, and can capture the excess kurtosis. Yet it is hard to estimate the mixture parameters [^1].

There is ongoing research into using techniques for examining the validity of modeling assumptions, such as extreme value theory [^0]. It would be assumed that during this course we would take a more historical approach (assuming normal or another common distribution) to learn models with a set of reduced complexities in our assumptions.

[0]: Longin, F. (2005). The choice of the distribution of asset returns: How extreme value theory can help?. Journal of Banking & Finance, 29(4), 1017-1035.

[1]: Tsay, R. S. (2014). An introduction to analysis of financial data with R. John Wiley & Sons.

[2]: Modern portfolio theory. (2016, January 6). In Wikipedia, The Free Encyclopedia. Retrieved 19:26, January 9, 2016, from https://en.wikipedia.org/w/index.php?title=Modern_portfolio_theory&oldid=698572860

[3]: Hudson, R. L. (2010). The (Mis) Behaviour of Markets: A Fractal View of Risk, Ruin and Reward. Profile Business.

[4]: Moment (mathematics). (2015, December 18). In Wikipedia, The Free Encyclopedia. Retrieved 19:18, January 9, 2016, from https://en.wikipedia.org/w/index.php?title=Moment_(mathematics)&oldid=695814896

[5]: Keating, C., & Shadwick, W. F. (2002). An introduction to omega. AIMA Newsletter.

# Week 2:

# Week 3:

# Week 4:

# Week 5:

# Week 6:

# Week 7:

# Week 8:

# Week 9:
