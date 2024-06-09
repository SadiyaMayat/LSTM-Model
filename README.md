## MRF Stock Price Prediction using LSTM
### Introduction
This Repository demonstrates how to use a Long Short-Term Memory (LSTM) neural network to predict the open stock price of MRF company. LSTM is a type of recurrent neural network (RNN) capable of learning long-term dependencies, making it suitable for time series forecasting, such as stock price prediction. In this, we utilize the historical stock data of MRF company to train an LSTM model. The features used for prediction include Open, High, Low, Close, Adjusted Close, and Volume. The model is trained to predict the next day's open stock price.
## Steps to Build the Model
### Data Preparation:
* Load the stock data from a CSV file.
* Normalize the data using Min-Max scaling.
* Create sequences of data points for training the LSTM model.
### Model Building:
* Construct an LSTM model using Keras with layers for LSTM, Dropout, and Dense.
* Compile the model with the Adam optimizer and mean squared error loss function.
### Model Training:
* Train the model using the prepared training data.
* Evaluate the model on the test data.
### Prediction and Evaluation:
* Make predictions on the test set.
* Calculate Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) to evaluate the model's performance.
* Predict the next day's open stock price using the latest data.
### Results
The notebook will output the Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) of the model's predictions. It will also plot the actual vs. predicted stock prices and print the predicted open price for the next day.
### Conclusion
This Repository provides a basic introduction to using LSTM for stock price prediction. It serves as a starting point for further exploration and enhancement in the field of time series forecasting and deep learning.
