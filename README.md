# Stock-market-trend-prediction-model
![image](https://github.com/Urmila2003/Stock-market-trend-prediction-model/assets/109129599/ccba64b4-4209-43c0-838e-4dc54c3b6817)

# Why do we need Stock Price Prediction?
The stock market is known for being volatile and hard to predict. Many researchers have attempted to use time-series data to forecast future stock prices, which could be highly profitable if successful. However, there are numerous variables that influence market fluctuations, and only a few can be accurately quantified, such as historical stock data, trading volume, and current prices. Other fundamental factors, like a company's intrinsic value, assets, performance, and strategies, can also impact investor confidence and stock prices, but they are difficult to incorporate into mathematical models. As a result, using machine learning for stock price prediction is challenging and can be unreliable. Additionally, unforeseen events, such as a pandemic or a war, can quickly impact the stock market, making accurate predictions even more difficult. Rather than trying to accurately predict exact values, analysts typically focus on making short-term predictions that provide a probability estimate of the market's future performance. By using historical data and relevant features, mathematical and machine learning models can forecast short-term fluctuations in the market on an average day.However, predicting the impact of unexpected events, such as market-shattering news, is extremely challenging.
![17507816814942577494445222649604](https://github.com/user-attachments/assets/e4435df3-71cf-4208-9128-3f6bb8be8769)

# Stock Price Prediction using Machine Learning
Using machine learning, stock price prediction involves forecasting the future value of stocks traded on stock exchanges to generate profits. Since there are numerous variables involved in predicting stock prices, achieving high accuracy is challenging, and that's where machine learning comes in handy.
![1750781643588785206214082860967](https://github.com/user-attachments/assets/bd2fcfe8-4798-4299-8213-ea5e03d7c558)

# Extracting the Stock Prices Dataset
We can use Pandas to load the downloaded CSV file into a DataFrame. Since each row corresponds to a specific date, we can index the DataFrame by the date column. The data we have collected spans from 22nd Feb 2022 to 22nd Feb 2023, which includes the unpredictable changes and after effects caused by the COVID-19 pandemic. This presents a challenge for our model to accurately predict stock prices during a period of significant market volatility. Plotting the High and Low points of the market, we see the below graph.
![image](https://github.com/Urmila2003/Stock-market-trend-prediction-model/assets/109129599/d924d4f7-65e1-4e5a-bce0-2fff5dc161d6)
