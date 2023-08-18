# Apple-Stock-Forecasting

Stock Price Prediction using SVR Models:
- This project employs Support Vector Regression (SVR) to predict stock prices based on historical data.
- Three SVR models are utilized: linear, polynomial (degree 2), and radial basis function (RBF), with a consistent hyperparameter value of C=1e3 for regularization.
- Three distinct SVR models are employed, enabling the exploration of diverse prediction strategies.

Data Collection and Visualization:
- Historical stock data is collected from a CSV file, containing dates and corresponding stock prices.
- The collected data is organized into separate lists for dates and prices, and the year portion of dates is extracted as integers.
- The project employs data visualization through matplotlib to showcase the historical data points and the predictions made by different SVR models.

Predictive Insights and Output:
- The SVR models are trained on the historical data to capture underlying patterns in stock price movements.
- Given a specific date (e.g., 29), the project predicts stock prices for that date using the trained SVR models.
- Predicted prices from the RBF, Linear, and Polynomial models are returned and displayed.
