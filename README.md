# Ethereum-Price-Prediction 
Capstone Project at Lighthouse Labs - Data Science
Predict Ethereum price based on blockchain information and compare the Deep Learning approach with regular ML algorithms.

### 1. Project Overview


### 2. Dataset

### 3. Evaluation
- We have a very good result with the LSTM model in Ethereum price prediction
  - R2 Score:  0.94
  - Mean Absolute Error:  215.07
  - Mean Squared Error:  92685.31
 
 ![](images/LSTM.PNG)
 
- We also have top 3 best regular machine learning models in predicting the Ethereum price:
  - Lasso Regression with the accuracy is 0.98
    - Mean Absolute Error: 86.27
    - Mean Squared Error: 17201.57
    - Mean Absolute Percentage Error (MDAPE): 4.24 %
    
  ![](images/Lasso.PNG)
  
  - Ridge Regression with the accuracy is 0.97
    - Mean Absolute Error: 146.38
    - Mean Squared Error: 43899.57
    - Mean Absolute Percentage Error (MDAPE): 4.24 %

  ![](images/Ridge.PNG)
  
  - Linear Regression with the accuracy is 0.95
    - Mean Absolute Error: 196.17
    - Mean Squared Error: 74505.19
    - Mean Absolute Percentage Error (MDAPE): 4.24 %

  ![](images/Linear.PNG)
  
### 4. Next Steps
