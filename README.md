# Time Series Anomaly Detection
Time Series Anomaly Detection in Network Traffic using Machine Learning Models

## Introduction
There are three major parts of the time series anomaly detection, which are data, problem statement, and model selection.

- Data: Seasonal network traffic data.

- Problem Statement: Clearly state which anomaly we want to detect.

- Model Selection: three different types

    - Statistical Methods: Use statistical techniques to identify anomalies based on deviations from a defined norm.

        ARIMA (AutoRegressive Integrated Moving Average): Captures the underlying trend and seasonality in the data to identify anomalies.
  
    - Machine Learning Methods: Leverage machine learning algorithms to detect anomalies.

        Supervised Learning: LOF, Prophet
      
    - Unsupervised Learning:

        Deep Learning Methods: Use neural networks for more complex data patterns.
      
        LSTM (Long Short-Term Memory) Networks: A type of recurrent neural network that can learn long-term dependencies and patterns in time series data.
      
        Autoencoders: Neural networks trained to compress and reconstruct data, where reconstruction errors can indicate anomalies.

      
