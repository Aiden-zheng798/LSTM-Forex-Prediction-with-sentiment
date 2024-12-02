# Foreign Exchange Market Prediction Based on Sentiment-Driven LSTM Modeling
This repository contains the code, data, and documentation for the project "Foreign Exchange Market Prediction Based on Sentiment-Driven LSTM Modeling", which integrates historical foreign exchange prices and sentiment analysis to enhance predictive accuracy.

## Overview
Accurate exchange rate prediction is crucial for financial decision-making and economic stability. This project employs Long Short-Term Memory (LSTM) models enhanced with sentiment analysis from financial news to predict trends in the Euro/US Dollar (EUR/USD) foreign exchange market. By combining historical data with relative sentiment indicators derived from VADER and DistilBERT, this approach achieves improved prediction accuracy.
![projet-image](https://github.com/user-attachments/assets/b77f0ac9-34d5-49e6-8249-6a6cba463201)
![image](https://github.com/user-attachments/assets/d3a53f1b-6e00-41a0-a928-b950c84f5286)

## Features
Sentiment Analysis: Analyzes news headlines with VADER and main text with DistilBERT.
LSTM Modeling: Optimized time-series prediction using random search for hyperparameter tuning.
Multi-Input Integration: Combines historical price data and sentiment vectors.
Performance Metrics: Achieves a 7.3% improvement in MAPE compared to models without sentiment data.


## Setup Instructions
1. Clone the repository
git clone https://github.com/Aiden-zheng798/LSTM-Forex-Prediction-With-sentiment.git
cd forex-sentiment-lstm

2. Install dependencies
Ensure you have Python 3.8 or later installed. Then run:
pip install -r requirements.txt


4. Prepare the data
Download the EUR/USD foreign exchange data from Yahoo Finance.
Use the src/preprocess.py script to clean and preprocess the data.
5. Run the model
Train the LSTM model with the following command:
python src/train.py --data_dir data/ --output_dir models/



## Key Results
Performance Improvement: Incorporating sentiment features reduced the MAPE by 7.3%.
Enhanced Understanding: The Relative Sentiment Index provided deeper insights into market dynamics.
Visualizations: Model predictions and evaluation metrics are stored in the results/ directory.


## function
- Support multi-currency forecasting
- Visualize the result output
- Efficient training and inference


## Table Of Content
1.CRISP-DM Stages
2.Data Collection
3.Exploratory Data Analysis
4.Bivariate Analysis
5.Correlation Matrix
6.Boxplots
7.Deployment
8.Optimization Routine
9.Cross-validation Strategy

