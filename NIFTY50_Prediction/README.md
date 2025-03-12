# NIFTY 50 Price Prediction  

## Overview  

This repository contains an implementation of **NIFTY 50 price prediction** using **LSTMs**. The model forecasts stock prices for the next **four days** with an accuracy of **99.57%**. **Keras Tuner** was used for hyperparameter optimization to achieve the best performance.  

## Implementation Details  

The model is based on a **Long Short-Term Memory (LSTM)** network, designed to capture temporal dependencies in stock price movements. The workflow includes:  

- **Data Preprocessing:** Historical NIFTY 50 price data is collected, normalized, and split into training and testing sets.  
- **Model Architecture:** A multi-layer **LSTM** network is used for sequential prediction.  
- **Hyperparameter Tuning:** **Keras Tuner** optimizes parameters such as the number of LSTM layers, neurons, learning rate, batch size and optimizers.  
- **Evaluation:** The model is tested on unseen data, achieving **99.57% accuracy** in predicting NIFTY 50 prices for the next four days.  

## Key Features  

- Implemented using **TensorFlow/Keras**.  
- Uses **LSTMs** for sequential data modeling.  
- **Keras Tuner** for hyperparameter optimization.  
- Trains on **historical NIFTY 50 daily data**.  
- Supports configurable hyperparameters such as the number of LSTM layers, neurons, batch size, and learning rate.  
