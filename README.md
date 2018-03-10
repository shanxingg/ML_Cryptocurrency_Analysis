# **Cryptocurrency Analysis and Prediction**

There are several paths one can take when deciding in which cryptocurrencies to invest, but a handful of these have risen to the top as the most popular options for investment, they are:

1. Bitcoin (BTC)
2. Ethereum (ETH)
3. Litecoin (LTC)
4. Bitcoin Cash (BCH)
5. Ripple (XRP)
6. Monero (XMR)
7. Zcash (ZEC)

Will BitCoin become ecnomic bubble?
What other cryptocurrencies that are worth to invest in?
How to maximize your short/long term investment gains?

In this analysis report, I performed exploratory data analysis to explore the cryptocurrency market. I also used machine learning algorithms to predict 30-days price of the most popular cryptocurrencies given their historical variations.
[access the notebook in jupyter nbviewer](#https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb)

![Cryptocurrency](http://www.bankingtech.com/files/2018/01/Cryptocurrencies.jpg)


# **Table of Content**

1. Prepare Data Set
 - Load Python Packages
 - Load and Prepare Data Set
 
[2. Data Quality Assessment](#2)
 - [Check Missing Values](#2-1)
 - [Check Duplicated Values](#2-2)

[3. Exploratory Data Analysis and Feature Engineering](#3)
 - [1.Market Capitalization and Transaction Volume](#3-1)
 - [2.Price Fluctuation of Cryptocurrencies](#3-2)
 - [3.Moving Averages and Price Trend](#3-3)
 - [4.Market Prices of Cryptocurrencies](#3-4)
 - [5.Return Ratio](#3-5)
 - [6.Candlestick Charts Using Plotly (BitCoin)](#3-6)

[4. Building Models - Predicting Price for Cryptocurrencies](#4)
 - [Prepare Data for Models](#4-1)
 - [Applying Machine Learning Models](#4-2)
 - [Prices Prediction](#4-3)

[5. Conclusion - Investment Suggestion](#5)
 - [How to maximize your short term investment gains?](#5-1)
 - [Whether to invest in cryptocurrency in the long term?](#5-2)

[6. Future Work](#6)

[7. Reference](#7)


# **Visualization Excerpts**

### 1. Bitcoin Price Simulation (2017.1 - 2018.3)
This notebook used plotly to visually show bitcoin stock price during the period from Jan. 2017 to Mar. 2018. This plot illustrates the moving average, volume of transaction, opening price, Bollinger Bands, as well as whether the price increases (blue) or decreases (grey).

![plotly](https://user-images.githubusercontent.com/31974451/37195543-21878f06-2328-11e8-9d24-68d488b85e9d.png)

### 2. Heatmap

Below is a correlation heatmap between eight most popular cryptocurrencies. One of the interesting findings is that all of them have a **highly positive correlation coefficience** (≥0.75), indicating all the cryptocurrencies  generally move in the same direction together along with the market.

Monero has the highest correlation coefficient of more than 0.85 with other cryptocurrencies. If the stocks of Bitcoin/Ethereum/Litcoin/Zcash pick up drastically, it is most likely that Monero will experience a similar boost as its fee-driven income picks up and positive earnings reports encourage investors.

Source: [How does correlation affect the stock market? | Investopedia](https://www.investopedia.com/ask/answers/021716/how-does-correlation-affect-stock-market.asp#ixzz59EdIHIh9)


![heatmap](https://user-images.githubusercontent.com/31974451/37195336-3f9ac86a-2327-11e8-8a67-09031834d063.png)

**Investment Advice:** The principal is that **inclusion of negatively correlated assets in a portfolio allows individuals to reduce the overall risk while still allowing for a positive return**. Therefore, to be able to build a diversified portfolio, investors are **not** advised to put all their money into cryptocurrencies market, rather they should diversify their assets into stock market, mutual funds and bank savings.




### 3. 30-days Bitcoin Price Prediction

![bitcoin prediction](https://user-images.githubusercontent.com/31974451/37195307-20924fce-2327-11e8-9027-98f854448a93.png)

**Investment Advice:**
Our 30-days forecast of bitcion price begins from Feb 25 2018, during which the predicted price is still volatile. Downward trending follows a short-term increasing momentum. Investors need to be cautious with the drastic price fluctuation as the price has already gone very high to a point of nearly $1,9000. **A short-term put option** and **a long-term call option** could be the potential preference of investors.
