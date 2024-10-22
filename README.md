BTC-bros
BTC-bros is a data pipeline project that fetches Bitcoin hourly OHLC (Open, High, Low, Close) data and the Fear and Greed Index from two different APIs. The data is streamed into Google BigQuery, where it undergoes processing and cleaning before being made ready for consumption. The processed data is then used to feed a machine learning model to predict the opening price of Bitcoin.

Project Overview
This project was created as part of a school assignment aimed at building end-to-end data pipelines and applying machine learning to financial data. The system collects data, processes it, and prepares it for predictive modeling.

Features
API Integration: Fetches hourly Bitcoin OHLC data and Fear and Greed Index from two separate APIs.
Data Storage: Streams raw data into a BigQuery table.
Data Cleaning: Cleans and processes the raw data to make it suitable for analysis and model consumption.
Machine Learning: A model is trained to predict Bitcoin's opening price based on the processed data.
