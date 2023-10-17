# [CMPS-3160 Final Project: Delays & Declines](https://colab.research.google.com/drive/1ykx4U-gtrlQJkSVl76oBoQXVIGYuWFI6?usp=sharing)
Happy Herold, Syed Mehran

This project is a collaboration between Happy Herold and Syed Mehran for CMPS-3160: Intro to Data Science. The authors intend to investigate how airline operational performance can predict stock prices. To investigate, the authors have compiled data from the last 6 months on airline financials and performance.

**Project Goals:**

> Authors hope to learn about how operational inefficiency contributes to stock prices.

> Authors would also like to learn how soon the market responds to inefficiencies

> Authors want to investigate how one could use this data to develop a model that can predict price shifts due to inefficiency

**Milestone 1:**

The authors intend to investigate how airline operational performance can predict stock prices. The data sets for this project are stock market data obtained from Yahoo Finance and domestic flight data from the Bureau of Transportation Statistics TranStats Marketing Carrier On-Time Performance table. To investigate, the authors have compiled data from the last 6 months of available data (01/01/2023 to 05/31/2023) on airline financials and performance. With the exception of the aviation index the 9 major airlines from the stock market data correspond to the market carriers in the flight data.

Since the aim of this project is to predict the stock prices based on airline performance, the stock market data provides actual values of the stock prices. One of the questions that the project aims to answer is whether or not the performance of a stock can be predicted based on the performance of an airline, and does the performance of multiple airlines impact the stock price of a single airline. As part of the ETL process the daily returns for each stock were calculated and used in creating a correlation matrix for daily returns. Time series data of the trading volume, open price, and closing price were also plotted.

To measure airline performance in this project flight data from the Marketing Carrier On-Time Performance table. The flight data contains flight characteristics including date, market carrier, operating carrier, tail number, origin and destination, scheduled departure time, actual departure time, scheduled arrival time, actual arrival time, canceled and diverted flights as well as other key features of the flight. The flight data does not specifically include airline performance metrics. One of the questions that the project aims to answer is if an airline’s flight data can be used to create a metric that can quantify the performance of an airline and can these metrics be used to compare different airlines and be able to predict the stock price. During the ETL process daily number of flights, daily number of cancellations, and proportion of flights that are operated by the market carrier have been calculated using the flight data and plotted.

****Data Set Websites:****

[Marketing Carrier On-Time Performance Data](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGK)

[Yahoo Finance](https://finance.yahoo.com/)


https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGK

https://www.transtats.bts.gov/databases.asp?20=F&Z1qr_VQ=E&Z1qr_Qr5p=N8vn6v10&f7owrp6_VQF=D

https://www.nasdaq.com/market-activity/index/xal

https://money.usnews.com/investing/stocks/airlines

