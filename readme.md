## Stock Trend Predictor
This project focuses on predicting stock trends using historical stock price data and a Long Short-Term Memory (LSTM) neural network. The goal is to analyze and visualize the stock price patterns and make predictions for future stock prices.

## Dependencies
Make sure you have the following dependencies installed:

Streamlit
NumPy
Pandas
Matplotlib
DateTime
Scikit-learn
Keras
TensorFlow
yfinance
## Usage
Install the required dependencies mentioned above.

Run the app.py file using the Streamlit command:
arduino
Copy code
streamlit run app.py
Open the provided local URL in your web browser to access the Stock Trend Predictor web application.

Enter the stock ticker symbol of the desired company in the text input field.

The application will fetch the historical stock price data for the specified stock ticker from the Yahoo Finance API.

The data will be displayed in a table, along with various visualizations, such as the closing price vs. time chart, moving averages, and predicted vs. actual closing prices.

The predictions are generated using an LSTM model that has been trained on the historical stock price data. The model predicts future stock prices based on the input data.

Analyze the visualizations and predictions to gain insights into the stock trends and make informed decisions.

## Model Training
The LSTM model used for prediction is trained using historical stock price data. The model is trained on a portion of the data, and the remaining data is used for testing and validation.

The data is split into training and testing sets, with 70% of the data used for training.

The training data is scaled using MinMaxScaler to normalize the values between 0 and 1.

The LSTM model is loaded from the pre-trained keras_model.h5 file.

The model is tested on the testing data to generate predictions for future stock prices.

The predicted prices are scaled back to their original values for better interpretation and comparison.

The predictions are plotted against the actual prices to visualize the performance of the model.

## Limitations
The accuracy of the predictions depends on the quality and availability of historical stock price data.

# Results
![image](https://github.com/SouravRay17/Stock-Price-Predictor/assets/83729666/95b8e59b-9deb-4068-97e9-8ccfc1fafbba)
![image](https://github.com/SouravRay17/Stock-Price-Predictor/assets/83729666/533230bc-8750-49b0-b6dc-f4a8903ca75c)


Stock market trends are influenced by various factors, and this model does not take into account external factors such as news, market sentiment, or economic indicators.

The predictions should be used for informational purposes only and should not be considered as financial advice. It is recommended to consult with a qualified financial advisor before making any investment decisions.

## Author
Sourav Ray
