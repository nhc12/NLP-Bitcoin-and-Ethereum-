# NLP-Homework (Bitcoin and Ethereum)
1. Homework objective: Use deep learning recurrent neural networks to model bitcoin closing prices. One model will used the FNG indicators to predict the closing price while the second model used a window of closing prices to predict the nth closing price.
2. Performed the analysis following the starter code (added the blank starter code for reference)
3. LSTM Stock Predictor Using Closing Pricess:
    * Data Preparation: 
      * Set the random seed for reproducibility
      * Loaded the fear and greed sentiment data for Bitcoin
      * Loaded the historical closing prices for Bitcoin
      * Joined the data into a single DataFrame
      * Predicted Closing Prices using a 10 day window of previous closing prices
      * Used 70% of the data for training and the remaineder for testing
      * Reshaped the features for the model
    * Built and Trained the LSTM RNN:
      * Compiled the model
      * Summarized the model
      * Trained the model
    * Model Performance:
      * Evaluated the model
      * Made predictions
      * Plotted the real vs predicted values as a line chart
4. LSTM Stock Predictor Using Fear and Greed Index: replicated steps as above model but with Fear and Greed Index
5. Conclusion: no significant difference between both. Closer predictions using closing prices (at least following the trend) but need to have a longer period to train the model. 
6. Sources for inspiration: in-class assignments of NLP module
      
