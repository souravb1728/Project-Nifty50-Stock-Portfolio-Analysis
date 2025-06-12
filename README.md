# Nifty50-Stock-Portfolio-Analysis

Here we will analyze the Nifty50 stock data for last 10 years

- First we will perform descriptive analysis of the stocks based on various metrics and find the top stocks
- Next we will perform predictive analysis by creating a portfolio of stocks using Modern Portfolio Theory

**Source of the Data : https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data**

## Descriptive Analysis

#### 1> Finding Top 5 Stocks based on Volume traded
Analysis of stocks with visualization

#### 2> Finding Top 5 Stocks based on VWAP
Analysis of stocks with visualization

#### 3> Finding Top 5 Stocks based on Turnover
Analysis of stocks with visualization

#### 4> Finding Top 5 Stocks based on Delivery
Analysis of stocks with visualization

#### 5> Finding Top 10 Stocks based on Annual Return
Conclusion from the analyis : **SHREECEM and TITAN gives the best annual return respectively at 53% and 48%**

#### 6> Finding Top 10 Stocks based on least Annual Volatility
Conclusion from the analysis : **NTPC and DRREDDY are the stocks with lowest volatility with annual volatility of 30% and 32% respectively**

## Predictive Analysis

**Strategy to pick stocks for Portfolio**

A person or entity might have different risk apetite and one might choose stocks/trades based on this requirement. **We will follow a numerical approach to find the Return to Risk ratio for the investment and try to maximize the ratio.**

Here we pick all the Stocks which are common to both the lists obtained from *Top 10 stocks by Return* and *Top 10 stocks by Volatility* >> SHREECEM, ULTRACEMCO, MARUTI, ASIANPAINT

### We will create a portfolio consisting of 6 stocks

We pick one stock from Top 10 stocks by Return : TITAN (48%) and one more stock from Top 10 stocks by Volatility > DRREDDY (32%)

**The final portfolio with 6 Stcoks :**

*SHREECEM*

*ULTRACEMCO*

*MARUTI*

*ASIANPAINT*

*TITAN*

*DRREDDY*

## MPT or Modern Portfolio Theory
Now that we have figured out the stocks to invest, we need to find out how much amount to invest in which stocks. Here we will use Modern Portfolio Theory to find the optimal Return to Risk ratio of the investment. The idea is to iterate through a process of randomly assigning weights to the stocks and calculate the respective Return to Risk ratio.

### Minimum Volatility Portfolio 

Selecting optimal combination based on Minimum Volatility of the Portfolio

***Return to Risk ratio is 8.35***

ASIANPAINT - 22.7%

DRREDDY - 30.3%

MARUTI - 17%

TITAN - 5%

SHREECEM - 14%

ULTRACEMCO - 11%

### Highest Sharpe Ratio Portfolio

Selecting optimal combination based on Maximum Return to Risk ratio ( Taking into account a risk factor)

***Return to Risk ratio is 11.22***

SHREECEM - 64.6%

ASIANPAINT - 9.5%

TITAN - 9.5%

ULTRACEMCO - 7%

DRREDDY - 5%

MARUTI - 4.2%
