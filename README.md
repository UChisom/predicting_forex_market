## Forex Prediction Model

Implementation of a Random forest algorithm model to predict **stock prices** for the S&P 500 index.

### Workflow

> Here's a quick walkthrough on what to expect to do in this project:)

1. Data Preprocessing
   
- Load data using **yfinance** library and data cleaning techniques. 
- Create a target column for training the model
  
2. Model Training
   
- Create Random Forrest Regressor model with
- Tune parameters for increased accuracy on predictions
- Train the model using predefined training set and continiously evalute for __accuracy score__, __f1 score__, and __classification reports__
  
3. Backtesting
   
- Develop a __backtesting__ algorithm to evaluate model performance using large historical data (10+ years)
- Gather data from backtesting process for evaluation using the earlier mentioned metrics
  
4. Model Improvement
   
- Create new model parameters to improve the performace of the model
- Create new set of predictor variables to increase reliability and accuracy
  
5. Reporting
   
- Report model performance and reasoning behind improvement techniques adopted
