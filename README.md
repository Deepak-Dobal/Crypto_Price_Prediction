# Crypto_Price_Prediction

**Predicting the price of Bitcoin using a Recurrent Neural Network (RNN) with Gated Recurrent Units (GRU) or Long Short-Term Memory (LSTM)**
**cells is a common approach in the field of time series forecasting. Here's a general overview of how you could approach building such a model in Python**

1-**Collect and preprocess data**: Collect historical data on Bitcoin prices and other relevant features, such as trading volume and news sentiment.
    Preprocess the data by cleaning and scaling it appropriately for input into the neural network.

2-**Split data into training and testing sets**: Divide the preprocessed data into training and testing sets to evaluate the model's performance.
![download](https://user-images.githubusercontent.com/121633990/231550730-55e1bdb3-6168-46a0-a4bd-b00c9ff93ec3.png)


3- **Define the RNN model**: In Python, you can use the keras library to define an RNN model with GRU or LSTM cells.
  You can set the number of layers, number of neurons in each layer, and other hyperparameters of the model.
  ![newplot](https://user-images.githubusercontent.com/121633990/231551042-a2d9ce2a-78db-4ca2-ae59-3ceed6f912a4.png)


4- **Train the model**: Train the RNN model using the training data. You can use stochastic gradient descent (SGD) or other optimization algorithms to 
    minimize the loss function.
    ![1_yBXV9o5q7L_CvY7quJt3WQ](https://user-images.githubusercontent.com/121633990/231519092-1509ce88-64a9-4b45-ab12-d4d1d4a46306.png)


5- **Evaluate the model**: Use the testing data to evaluate the performance of the RNN model. You can calculate various metrics, 
    such as mean squared error (MSE) and mean absolute error (MAE), to measure the accuracy of the model's predictions.
    These are the evaluation metrics for two different models trained on the same data:
    
    
**LSTM Model Evaluation:**

MSE: 24469439.631619945

RMSE: 4946.659441645437

MAE: 1938.9612872579823

**GRU Model Evaluation:**

MSE: 11028995.233338801

RMSE: 3320.993109498844

MAE: 1280.847861115829

From the given evaluation metrics, it appears that the GRU model performs better than the LSTM model as it has a lower MSE, RMSE, and MAE.
    



**Keep in mind that predicting stock prices, including Bitcoin, is a complex and difficult task that relies on many factors beyond historical prices and trading volume.
Therefore, the accuracy of the predictions may vary, and it's important to use caution when making investment decisions based on the model's predictions.**
