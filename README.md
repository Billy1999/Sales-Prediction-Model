# Sales Forecasting Model
### Problem Statement:

Predicting Daily Sales for a Retail Store Using a Regression Machine Learning model

#### Objective:

To develop a machine learning model that accurately predicts daily sales for a retail store based on historical sales data, store identifiers, item identifiers, and date features.

Background: Retail businesses rely heavily on accurate sales forecasting to manage inventory, optimize staffing, and improve customer satisfaction. By predicting future sales, a store can ensure that popular items are in stock, reducing the likelihood of stockouts, and manage excess inventory, reducing waste and storage costs. This project aims to use historical sales data to build a predictive model that can forecast daily sales for each store-item combination.

### Data:

The dataset consists of historical sales records, including the following features:

date: The date of the sales record.

store: The identifier for the store.

item: The identifier for the item.

sales: The number of units sold.

### Problem:

Develop a regression model using the CatBoost algorithm to predict the daily sales for a given store and item on a specific date. The model should learn from historical sales data and be able to generalize well to future dates, providing accurate predictions.

### Challenges:

Seasonality and Trends:
Sales data often exhibit seasonal patterns and trends that need to be captured by the model.

Store and Item Variability:
Different stores and items may have distinct sales patterns, requiring the model to handle this variability.

Data Preprocessing:
Proper handling of date features, such as extracting day of the week, month, and year, is crucial for improving model performance.

Evaluation:
The model's performance will be evaluated using the Mean Absolute Percentage Error (MAPE) to ensure it provides reliable predictions.

### Goals:

Preprocess the data to ensure it is suitable for training a regression model.
Train a CatBoostRegressor model on the historical sales data.
Evaluate the model's performance using MAPE.
Perform predictions using raw input.
