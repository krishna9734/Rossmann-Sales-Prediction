# Rossmann-Sales-Prediction
Predicting the daily sales for Rossmann store chain
Rossmann operates over 3,000 drug stores in 7 European countries. Currently,
Rossmann store managers are tasked with predicting their daily sales for up to six
weeks in advance. Store sales are influenced by many factors, including promotions,
competition, school and state holidays, seasonality, and locality. With thousands of
individual managers predicting sales based on their unique circumstances, the
accuracy of results can be quite varied.
With historical sales data for 1,115 Rossmann stores, where we need to explore and
analyze the data to forecast the "Sales" column for the test set.
In the first step, import two of the raw data and merged both the dataset “Rossmann
Stores Data.csv” and “store.csv” for further implementations. And then check
statistical properties, Know the shape and size of the dataset and perform data
wrangling over It which includes splitting the Date column into Year-Month-Day and
week of year.
In the second step, perform the exploratory data analysis in which discover the
relationships between sales and other features (e.g., Day of week, Promos, State
holidays, Store types) followed by data visualization and data interpretation which
involves finding patterns and dependency of variables.
In the third step, preprocess the data through correlation heatmap, encode (One Hot
Encoding) the categorical features, standardize the variables, check the distribution of
the outliers, and split the data into train and test sets. After which data modeling
takes place where the data fits through Linear Regressor, Decision Tree Regressor,
Random Forest Regressor, XG Boost, and Gradient Boosting algorithms.
And at the last, the ML regression project concluded by revealing that the Random
Forest Regressor model gave the best results with the highest Test R2 and lowest Test
RMSE scores. From the feature importances, it is noted that the features Customers,
CompetitionDistance, StoreType_d, and Promo are the four most important factors
which determine Sales.
