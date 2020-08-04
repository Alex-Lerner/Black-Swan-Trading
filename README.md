# Black-Swan-Trading

This repository contains 3 files.
- portfolio.py is the connector to the Database
- beta_final_bucket.py contains the logic of the trading strategy
- functions 

There a numerous studies claiming that the markets do not follow the so called random walk
hypothesis. In fact many market participants believe the markets are momentum trending or
mean reverting. This thesis aims to further explore both of these behaviours and determine what
process the S&P 500 follows.

This thesis also evaluates a long/short equity trading strategy by investing in the top and bottom
10% of the stocks listed in the S&P 500 exploiting market's reaction after unpredictable Black
Swan events. This will also test the efficient market hypothesis and if beta is a valuable tool for
portfolio selection. The active strategy yields a 91.2% increase while buying and holding the
S&P 500 yielded 85.2% between 2007 and 2018. Other results include that neither the daily
returns of the S&P 500 and the active strategy were represented by the normal distribution.

This thesis is unable to reject the null hypothesis stating that the markets follow the random
walk hypothesis. Three tests were taken including the autocorrelation function of the returns,
Hurst exponent and Augmented Dickey Fuller test. When assessing this as a whole there are
different results depending on the tests that was carried. When assessing the autocorrelation
function there are initial insights that the markets are mean reverting when testing for daily,
weekly and yearly returns. However monthly returns yield a positive autocorrelation meaning
that it is behaving as a momentum trending process. It's also important to note that at none of
these time scales the yield a large absolute value for the autocorrelation having a low
confidence level that the markets are not following the random walk hypothesis.
The Hurst exponent for the S&P 500 resulted to be slightly under 0.5, being in the region of
mean reversion. To validate our function this was also tested using a simulation of a Geometric
Brownian Motion, mean reverting process and momentum trending. This shows how the Hurst
exponent the mean reverting process tends to zero and the Hurst for the momentum trending
tends to one.

Lastly the Augmented Dickey-Fuller test was computing giving a positive ADF statistic for the
S&P 500. Interestingly the value is far away from the 1%, 5% and 10% critical value. This
means that this test cannot reject the null hypothesis. Overall our results also conflict with each
other showing how hard it is for investors to find and exploit market insights.

Second part of this thesis takes the assumption that markets are mean reverting. When defining
a Black Swan event at 3% the active equity trading strategy was able to outperform the
benchmark index. This shows that beta is a valid tool for portfolio selection and brings further
evidence that the markets could be mean reverting. However these returns are not significantly
higher than the benchmark index meaning that the associated transaction costs could make this
strategy less profitable than the benchmark index.

We conclude that there still has to be further research to determine if the markets follow the
random walk hypothesis. Secondly, there is further evidence that beta is a valid tool for portfolio
selection when testing for our active trading strategy.
