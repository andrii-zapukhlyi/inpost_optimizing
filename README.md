# Optimizing InPost Logistics with Neural Networks and Machine Learning

## Objective
The goal of this project is to optimize InPost logistics by forecasting the daily number of parcel shipments using multiple data sources. These include historical shipment volumes, client-provided forecasts, date-specific attributes, and weather conditions. By developing a robust predictive model, this solution aims to enhance planning accuracy, streamline logistics operations, and support data-driven decision-making.

## Solution
The solution involves preprocessing, visualizing, and analyzing the data, followed by the development of various time-series forecasting models. These models will include SARIMA, Prophet, gradient boosting algorithms, tree-based models, and Artificial Neural Networks.

## Dataset Overview
The data consists of 4 datasets containing various information from January 2021 to September 2023:

- dimDates.csv: Includes information about days, such as year, month, day of the week, holiday indicators, and other date-related attributes.
- Posting_volumes.parquet: Contains parcel volume data from January 2021 to September 2023 with separated X client.
- X_ClientORDERS.xlsx: Provides X client's predictions for parcel volumes starting from January 2023.
- Folder Temp: Includes daily weather data for the same period.

## Conclusion
In conclusion, this project successfully optimized InPost logistics by developing a robust predictive model for forecasting daily parcel shipments. By integrating multiple data sources, including historical shipment volumes, client forecasts, date-specific attributes, and weather conditions, the model significantly improved planning accuracy. Additionally, the GRU and LSTM models outperformed other algorithms, achieving the best performance in terms of forecasting accuracy.
