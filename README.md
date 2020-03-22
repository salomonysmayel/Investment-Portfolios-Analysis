## Investment Portfolios Analysis 

Analysis of different portfolios to determine which outperformes the others on: volatility, returns, risk, and Sharpe ratios. Two algorithmic trading portfolios (algo1 and algo2), four that represent the portfolios of famous "whale" investors like Warren Buffett, and some from big hedge and mutual funds, as well as a custom portfolio and the S&P 500.

### Libraries used on this Project:

**Pandas**

**Numpy**

**Matplotlib** 


                                             Portfolios Returns Dataframe

![supply_chain](/images/1.png)

![supply_chain](/images/2.png)


Conduct Quantitative Analysis

Analyze the data to see if any of the portfolios outperform the stock market (i.e., the S&P 500).

Performance Analysis

Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?


Risk Analysis


Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?


Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?



Rolling Statistics


Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does risk increase for each of the portfolios at the same time risk increases in the S&P?


Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?


Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?



Plot Sharpe Ratios
Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. (After all, if you have two portfolios that each offer a 10% return, yet one is lower risk, you would invest in the lower-risk portfolio, right?)


Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.


Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.



Create Custom Portfolio
Harold is ecstatic that you were able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales portfolios. However, now you are wondering whether you can choose your own portfolio that performs just as well as the algorithmic portfolios. Investigate by doing the following:


Visit NASDAQ's Historical Price Data and choose 3-5 stocks for your own portfolio.


Download the data as CSV files and calculate the portfolio returns.


Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?


## Results

![supply_chain](/Images/network_create.png)


### Conduct Quantitative Analysis

Analyze the data to see if any of the portfolios outperform the stock market (i.e., the S&P 500).

#### Performance Analysis

1. Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?

All portfolios end up outperforming the S&P500, but not though the whole plot, at some points in time the S&P 500 outperform other portfolios. Around April 2016 S&P 500 is outperforming all but Algo1 portfolio.

#### Risk Analysis

1. Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?

Considering all data points, the portfolio with the smallest spread seems to be PAULSON & CO.INC.while Berkshire has the largest spread

2. Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?

Portfolios that are riskier than S&P 500 are TIGER GLOBAL MANAGEMENT LLC and BERKSHIRE HATHAWAY INC.

#### Rolling Statistics

1. Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does risk increase for each of the portfolios at the same time risk increases in the S&P?

In general the risk of portfolios follow the same pattern as time goes by, but looking up close we can find some portfolios that increase risk while S&P 500 decreases risk. Between 2015-07 and 2016-01 We can see that for some time risk for S&P 500 was increasing as Algo1 risk was decreasing. But I would say that in general it seems all portfolios tend to go along in terms of risk variation but if you consider bigger intervals of time.

2. Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?

PAULSON & CO.INC. is the portfolio that most closely mimics the S&P. With the highest correlation value of 0.013549

3. Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?

If you study the rolling Beta for BERKSHIRE HATHAWAY INC. you can see that it moves in some relation with the risk variation for the S&P 500. For example, for 2018-01 S&P 500 had a very low risk for the S&P compared to other dates, for this low risk, beta was close to 1, meaning that the risk of both market and portfolios were close. on the other hand, between 2015-07 and 2016-01 beta was low, and the risk for S&P is high, so the risk of the market and the risk of portfolio seem to be opposing. It seems BERKSHIRE HATHAWAY INC. is playing safe when the market gets risky and going bold when the market is safe.

### Plot Sharpe Ratios

Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. (After all, if you have two portfolios that each offer a 10% return, yet one is lower risk, you would invest in the lower-risk portfolio, right?)

1. Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.

2. Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.

Algo1 outperforms all portfolios. Algo2 outperforms all but BERKSHIRE HATHAWAY INC (And Algo1)

CUSTOM PORTFOLIO ANALYSIS

For cumulative returns, custom portfolio ends up outperforming all other portfolios. Is riskier that all but BERKSHIRE HATHAWAY INC. Beta for custom portfolio tends to grow when the market gets less risky. It has a high sharpe ratio compared to the other portfolios, except for ALGO1. Custom portfolio is more correlated with Algo2 portfolio with a corr value of 0.755, meaning that for the return this portfolio generated is worth taking the risk compared to the other portfolios with less Sharpe ratios, except for Algo2 portfolio.
