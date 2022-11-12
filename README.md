# STOCKERS

TEAM MEMBERS:
Alexei Beuno H |https://github.com/Alexeibeuno
Rashmi S
Sneha T |https://github.com/Sneha1221
Murrel Miranda
Shrimanta Satpati
Shivanshi Maheshwari

ABSTRACT:
Stock market also called as the equity market is the aggregation of sellers and buyers. It is concerned with the domain where the shares of various public listed companies are traded. For predicting the growth of economy, stock market acts as an index. Due to the nonlinear nature, the prediction of the stock market becomes a difficult task. But the application of various time series models has been becoming a powerful source for the prediction. These techniques employ historical data of the stocks for the training of time series models and help in predicting their future behavior.

Link to the Stock-ers app: https://alexeibeuno.shinyapps.io/Stock-ers/?_ga=2.92594909.1126649841.1650303251-1011494410.1644594405

PROBLEM STATEMENT:
1.	To forecast closing prices of 30 companies under nifty fifty stocks for about 90 days.
2.	To understand trends and patterns underlying in the historical data of each of the 30 companies.

DATA SOURCE:
We have obtained the datasets from yahoo.finance.com. We use real time data that shows the updated price or volume information on a tick-by-tick or minute-by-minute basis for stocks that trade on the exchange.
The companies listed under Nifty-fifty stocks that we are using for analysis are as given below:
1.	TCS (Tata Consultancy Services Limited)
2.	BAJAJFINSV (Bajaj Finserv Limited)
3.	WIPRO (Wipro Limited)
4.	TITAN (Titan Company Limited)
5.	ONGC (Oil and Natural Gas Corporation Limited)
6.	INFY (Infosys Limited)
7.	CIPLA (Cipla Limited)
8.	HCLTECH (HCL Technologies Limited)
9.	RELIANCE (Reliance Industries Limited)
10.	TECHM (Tech Mahindra Limited)
11.	M&M (Mahindra and Mahindra Limited)
12.	BAJAJ-AUTO (Bajaj Auto Limited)
13.	HEROMOTOCO (Hero MotoCorp Limited)
14.	EICHERMOT (Eicher Motors Limited)
15.	MARUTI (Maruti Suzuki India Limited)
16.	LT (Larsen & Toubro)
17.	ICICIBANK (Industrial Credit and Investment Corporation of India)
18.	AXISBANK (Axis Bank Limited)
19.	KOTAKBANK (Kotak Mahindra Bank Limited)
20.	INDUSINDBK (INDUSIND Bank Limited)
21.	BAJFINANCE (Bajaj Finance Limited)
22.	HINDUNILVR (Hindustan Unilever Limited )
23.	NESTLEIND (Nestle India Limited)
24.	PIDILITIND (Pidilite Industries Limited)
25.	BERGEPAINT (Berger Paints India Limited)
26.	DABUR (Dabur India Limited)
27.	COLPAL (Colgate-Palmolive India Limited)
28.	GODREJCP (Godrej Customer Products Limited)
29.	HAVELLS (Havells India Limited)
30.	AAPl (Apple)


METHODOLOGY:
A. The simplest approach to understand the stock market time series data that we have is to do so by data visualization.
1. A simple time series plot
2. MACD (Moving Average Convergence Divergence)
3. Decomposition of Time series Plot
4. Candle Stick Chart
5. Golden Crosses
6. Ichimoku Cloud
7. Relative Strength Index
8. Bollinger Bands

B. Methods used for forecasting close prices of a company
1.	ARIMA Model (Auto Regressive Integrated Moving Average Model)
2.	Prophet Model

C. Test to check accuracy of our forecasts
1. ADF Test
2. Box-Ljung Test

This is how the UI looks like:
1. Home tab:
![1](https://user-images.githubusercontent.com/67053046/195774161-5f2a69b8-9e7f-4fde-b713-4325c754db2a.PNG)

2. Data Visualization tab:
![2](https://user-images.githubusercontent.com/67053046/195774259-51872fdf-242f-445c-a1d1-e89a593ccec2.PNG)

3. Arima Forecast:
![3](https://user-images.githubusercontent.com/67053046/195774317-79d842b0-ef23-4637-8658-da3a7ff1c795.PNG)

4. Arima Components:
![4](https://user-images.githubusercontent.com/67053046/195774388-9a449b85-ad76-47d9-ab3c-6e97e17d5c05.PNG)

5. Market Indicators:
![5](https://user-images.githubusercontent.com/67053046/195774469-dab65ffb-aa16-48a8-9f5c-cfef05416740.PNG)

6. Adf and Box-Ljung test:
![6](https://user-images.githubusercontent.com/67053046/195774547-4ed05e81-1955-434a-83b4-73953da8e2c2.PNG)

7. Prophet model and it's components:
![7](https://user-images.githubusercontent.com/67053046/195774628-9d9ea747-0d7b-4499-ab48-1b390edd03e6.PNG)




