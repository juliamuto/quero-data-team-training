# Training Exercise: Build a Medallion Architecture with Data from the StockData API

## About
This project is part of a training exercise for members of the Data Analytics team at Quero Education. The goal is to practice working with APIs, data pipelines, and the medallion architecture.

### Objective
- Pull data from an API (StockData API) and store it using a medallion architecture consisting of three layers: Bronze, Silver, and Gold.
- Implement both full and incremental data loads for the database.

### Expected Results
1. **Full Load**: Code that pulls historical stock price data for at least 10 different companies (with a minimum of 10 days' worth of data).
2. **Incremental Load**: Code that can be used to regularly update the database with the latest stock data.
3. **Medallion Architecture**: Organize the data using the medallion architecture model:
   - **Bronze**: Raw, unrefined data directly from the API.
   - **Silver**: Cleaned, transformed, and partially processed data.
   - **Gold**: Final, aggregated, and ready-to-use data for analysis or reporting.
4. **Data Visualization**: A line graph that plots the history of stock prices for the selected companies over time.
