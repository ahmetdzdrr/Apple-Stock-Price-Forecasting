# StockPriceForecasting

In this project, a prediction was made on the closing price of Apple stock by considering the purchase of shares. The prediction was attempted using LSTM, GRU, and LSTM&amp;GRU models, based on a 7-year data analysis, to determine the closing price for the next 30 days.


![Investing-How-To-Buy-Apple-Stock](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/e54a9b01-df55-4e44-8f65-2b5628906e7b)

DATA RETRIEVAL

Apple stock data was retrieved and downloaded from Yahoo Finance, considering the years 2016 to 2023.

DATA PREPROCESSING

Since the "Adj Close" and "Close" columns were identical, the "Adj Close" column was removed, and the "Close" column was considered as the target variable.
![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/054527a2-e6e7-4297-9760-c6ef7fc1c9a2)

DATA PREPARATION

After data preprocessing, the data was divided into training and testing sets. The data was split with a ratio of 70% for training and 30% for testing.

LSTM MODEL BUILDING

An LSTM model based on RNN was constructed as the model. With the help of Keras, this model utilized 3 hidden layers, 1 dropout layer, and 1 output layer.

![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/df37f80b-5a25-4db5-8d32-55e0f116fcf1)
![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/83a56b10-40ac-4680-9f43-45748bf08297)

LSTM MODEL FORECASTING (NEXT 30 DAYS WTIH 180 DAYS BACKTEST)

![Ekran görüntüsü 2023-07-02 214121](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/7bd312eb-180a-4c04-a6f1-87daf9e616e0)


GRU MODEL BUILDING

Similar to the LSTM model, the GRU model was also constructed and trained in a similar manner.

![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/7c7d20d0-1e40-4574-b39d-be3c615e7e20)
![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/fa87f4a5-8651-4823-8519-bb9298a6b98f)

GRU MODEL FORECASTING (NEXT 30 DAYS WTIH 180 DAYS BACKTEST)

![Ekran görüntüsü 2023-07-02 221704](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/9586df1c-d45d-4af2-8137-7268960d3f0e)

LSTM & GRU MODEL BUILDING

In addition to the LSTM and GRU models, a combined model incorporating both LSTM and GRU was constructed, and training and testing were performed.

![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/e0677e85-d881-4636-ba98-f8edc1eecad0)
![download](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/13705321-b0ce-41cd-806d-66fb96452757)

LSTM & GRU FORECASTING (NEXT 30 DAYS WITH 180 DAYS BACKTEST)

![Ekran görüntüsü 2023-07-02 223901](https://github.com/ahmetdzdrr/StockPriceForecasting/assets/117534684/7ef1f4d0-7874-49ef-a0dc-c39e489236b5)
