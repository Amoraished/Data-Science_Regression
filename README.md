# Regression_Project
Data science Project one of core element of T5 Boot camp from SDAIA Academy
# saudi_stocke_exchange
<p align="center" width="100%">
<img src="https://m.eyeofriyadh.com/news_images/2018/07/9c94765b7e84.jpg" width="550" length="100" style="display: block; margin: 0 auto"/>
</p>

# Problem Statement

Using data science in the stock market is not new, but that doesn't apply for Saudi Stock Exchange (Tadawul), It needs to be explored and studied deeply, so we can cluster companies based on its behavior during the good and bad days. Also we can identify the days with a very large number of trades and try to understand the reason behind it. Finally we can predict the stocks prices.

# Dataset
To achieve the goal of this study the dataset California Housing Prices will be used. This dataset can be found at [Kaggle](https://www.kaggle.com/salwaalzahrani/saudi-stock-exchange-tadawul?select=Tadawul_stcks.csv).
There is 593820 rows and 12 columns.

symbol (Integer): The symbol or the reference number of the company.
name(String): Name of the company.
trading_name (String): The trading name of the company.
sectoer (String): The sector in which the company operates.
date (Date): The date of the stock price.
open (Decimal): The opening price.
high (Decimal): The highest price of the stock at that day.
low (Decimal): The lowest price of the stock at that day.
close (Decimal): The closing price.
change (Decimal): The change in price from the last day.
perc_Change (Decimal): The percentage of the change.
volume_traded (Decimal): The volume of the trades for the day.
value_traded (Decimal): The value of the trades for the day.
no_trades (Decimal): The number of trades for the day.


The sample of data is shown in the following table:

<table width="100%">
 <tr>
  <th>trading_name</th><th>sectoer</th><th>date</th><th>open</th><th>high</th><th>low</th><th>close</th><th>change</th><th>perc_Change</th>
 <th>volume_traded</th><th>value_traded</th><th>no_trades</th>
 <tr>
  <th>SARCO</th><th>Energy</th><th>3/5/2020</th><th>35.55</th><th>35.85</th><th>34.9</th><th>34.9</th><th>-0.4</th><th>-1.13</th><th>436609</th><th>15399073.5</th><th>804</th></table>

## Tools
There are tools that will be used to achieve the goal of this study, such as: 
- Numpy
- Pandas
- Matplotlib
- Seaborn
- math
- sklearn.preprocessing
- sklearn.model_selection
- LinearRegression
- DecisionTreeRegressor
-  mean_squared_error
The work will be done through Jupyter notebook.

## GOALS
- predict the stocks prices
- What is the highest profit section?
- What is the most valuable year in the Saudi stock market? 
- What is the less valuable year in the Saudi stock market?
- What is the percentage change in the sector, and what is the highest sector?


## Authors 
- [@elaftalal](https://github.com/elaftalal)
- [@Alya ALmanqour](https://github.com/Alya11salem)
- [@Amoraished](https://github.com/Amoraished)
