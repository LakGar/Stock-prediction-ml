# Stock Price Prediction using Machine Learning

This project uses a Long Short-Term Memory (LSTM) based deep learning model to predict stock prices. It utilizes historical stock price data to make predictions about future stock prices for a specific company. In this example, we use historical stock price data for TATA Global Beverages.

Table of Contents

1. Introduction
2. Dataset
3. Setup
4. Usage
5. Model Architecture
6. Results
7. Contributing
8. License

Introduction

Stock price prediction is a common problem in financial and data analysis. This project demonstrates a simple implementation of a stock price prediction model using deep learning techniques. It uses the Keras library to build an LSTM-based neural network for time series forecasting.

Dataset

We use historical stock price data for TATA Global Beverages. The dataset can be found at the following URLs:

Training Data: NSE-TATAGLOBAL.csv
Testing Data: tatatest.csv
The training data contains historical stock price information, while the testing data is used to evaluate the model's performance.

Setup

Before running the code, you need to set up your Python environment and install the required libraries. You can do this using the following commands:

    pip install numpy pandas matplotlib scikit-learn keras

Usage

Clone this repository to your local machine:

    git clone <repository-url>
    
Run the Jupyter Notebook or Python script provided to train and test the stock price prediction model.

Model Architecture

The model architecture consists of multiple LSTM layers with dropout regularization to prevent overfitting. Here is a summary of the architecture:

Input Layer: LSTM with 50 units (returning sequences)
Dropout Layer: 20% dropout rate
LSTM Layer: 50 units (returning sequences)
Dropout Layer: 20% dropout rate
LSTM Layer: 50 units (returning sequences)
Dropout Layer: 20% dropout rate
LSTM Layer: 50 units
Dropout Layer: 20% dropout rate
Output Layer: Dense layer with 1 unit

The model is compiled with the Adam optimizer and mean squared error loss.

Results

After training the model on the training data, it is evaluated on the testing data. The predicted stock prices are compared to the actual stock prices, and the results are visualized using Matplotlib.

Contributing

If you would like to contribute to this project, please open an issue or submit a pull request. We welcome improvements, bug fixes, and new features.

License

This project is licensed under the MIT License - see the LICENSE file for details.


