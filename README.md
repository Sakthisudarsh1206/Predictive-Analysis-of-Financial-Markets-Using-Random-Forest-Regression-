**Financial Market Prediction with Random Forest Regression**

This project aims to predict financial market trends using machine learning techniques, specifically Random Forest Regression. The model is trained on historical market data and sentiment analysis of news articles. The goal is to forecast the closing prices of a specific financial asset (e.g., stock, commodity) based on various features such as historical prices, sentiment scores, and other relevant metrics.
**Here HDFC stocks were taken into consideration, the dataset was self acquired using Web scraping of news articles in yahoo financial news, and the stock closing prices from yahoo finance. Other factors such as Gold Prices,USD-INR Exchange Rates,Fuel Prices were also considered for better analysis stock movement**

**Overview**
The project consists of the following main components:

Data Collection: Historical market data and sentiment analysis data from news articles are collected and preprocessed.
Data Preprocessing: Data is cleaned, missing values are handled, and features are engineered for training the model.

Model Training: The Random Forest Regression model is trained on the preprocessed data to learn the relationship between input features and target variable (closing prices).

Model Evaluation: The trained model is evaluated using various metrics such as Mean Squared Error (MSE) to assess its performance.

Prediction and Risk Assessment: The model is used to make predictions on unseen data, and a risk assessment function is applied to evaluate investment decisions based on predicted prices and historical trends.

**Dependencies**
The project relies on the following dependencies:

Python 3.x
pandas
numpy
matplotlib
scikit-learn

**Usage**
Ensure that the historical market data and sentiment analysis data are available in CSV format. Update the file paths in the script accordingly.
Run the finalmodel.ipynb Jupyter Notebook to execute the entire pipeline, including data preprocessing, model training, evaluation, and prediction.
Modify the parameters and hyperparameters in the script as needed to experiment with different configurations.

**Contributing**
Contributions to this project are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.
