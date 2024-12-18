# Training Exercise: Build a Medallion Architecture with Data from the StockData API

## About
This project is part of a training exercise for members of the Data Analytics team at Quero Education. The goal is to practice working with APIs, data pipelines, and the medallion architecture.

### Objective
- Pull data from an API (StockData API) and store it using a medallion architecture consisting of three layers: Bronze, Silver, and Gold.
- Implement both full and incremental data loads for the database.
- Create graph that shows average prices of selected stock on a timeline

### Required Python libraries
- Pandas
- json
- requests
- pyarrow
- matplotlib
- ploty

### Folder structure
- bronze:
    - contains jupyter notebooks for the full and incremental loads of API data and the bronze json archive that stores it
- silver:
    - transforms the bronze json into a silver parquet
- gold
    - transforms the silver parquet into a gold parquet, with the average price for a given stock on a given day. Also contains the notebook that plots the graph with the data
