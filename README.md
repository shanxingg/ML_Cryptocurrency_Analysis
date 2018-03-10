# **Cryptocurrency Analysis and Prediction**

There are several paths one can take when deciding in which cryptocurrencies to invest, but a handful of these have risen to the top as the most popular options for investment, they are:

1. Bitcoin (BTC)
2. Ethereum (ETH)
3. Litecoin (LTC)
4. Bitcoin Cash (BCH)
5. Ripple (XRP)
6. Monero (XMR)
7. Zcash (ZEC)

Will BitCoin become ecnomic bubble?<br>
What other cryptocurrencies that are worth to invest in?<br>
How to maximize your short/long term investment gains?<br>

In this analysis report, I performed exploratory data analysis to explore the cryptocurrency market. I also used machine learning algorithms to predict 30-days price of the most popular cryptocurrencies given their historical variations.<br>

[Access the notebook in jupyter nbviewer](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb)


![Cryptocurrency](http://www.bankingtech.com/files/2018/01/Cryptocurrencies.jpg)



## **Table of Content**

[1. Prepare Data Set](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#1)
 - Load Python Packages
 - Load and Prepare Data Set
 
[2. Data Quality Assessment](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#2)
 - Check Missing Values
 - Check Duplicated Values

[3. Exploratory Data Analysis and Feature Engineering](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#3)
 - Market Capitalization and Transaction Volume
 - Price Fluctuation of Cryptocurrencies
 - Moving Averages and Price Trend
 - Market Prices of Cryptocurrencies
 - Return Ratio
 - Candlestick Charts Using Plotly (BitCoin)

[4. Building Models - Predicting Price for Cryptocurrencies](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#4)
 - Prepare Data for Models
 - Applying Machine Learning Models
 - Prices Prediction

[5. Conclusion - Investment Suggestion](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#5)
 - How to maximize your short term investment gains?
 - Whether to invest in cryptocurrency in the long term?

[6. Future Work](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#6)

[7. Reference](https://nbviewer.jupyter.org/github/shanxingg/ML_Cryptocurrency_Investments/blob/master/Analysis_of_Cryptocurrency_Investments.ipynb#7)



## **Visualization Excerpts**

### 1. Candlestick Chart for Bitcoin
This notebook used plotly to visually show bitcoin stock price during the period from Jan. 2017 to Mar. 2018.<br>

![Candlestick](https://user-images.githubusercontent.com/32560872/37240662-81868c64-2403-11e8-8812-ddad29c2fa9e.png)


### 2. Price Fluctuation of Cryptocurrencies
This notebook used matplotlib to visually show opening, closing, highest, and lowest stock price for each of the cryptocurrency.<br>

![Price_Fluctuation](https://user-images.githubusercontent.com/32560872/37240755-811b5844-2404-11e8-8add-7acc17e7b9ce.png)


### 3. Correlation Heatmap of Cryptocurrencies
This notebook used seaborn to visually show pearson correlation coefficient to explore if BitCoin price influences price of other cryptocurrencies.<br>

![Correlation_Heatmap](https://user-images.githubusercontent.com/32560872/37240849-9fe03122-2405-11e8-8a14-2e7833285f57.png)


### 4. Prices Prediction for Bitcoin
This notebook used matplotlib to visually show 30-days price prediction for Bitcoin.<br>
![Prediction](https://user-images.githubusercontent.com/32560872/37240880-0f18a8d0-2406-11e8-92cf-e97e42fd132a.png)
