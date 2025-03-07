# Solana (SOL) Price Prediction using Regression Models - Python
In this project we are going to test which is the best Regression model to give the predicted price close to the real price of Solana. For this test,  we are using  365 day historic data of Solana. We have downloaded the dataset from Coinmarketcap. The downloaded csv file is imported to excel and did the cleaning. The cleaned file to imported to jupyter notebook and we did the analysis.

At first, we plot a graph with Date and Close Price to understand how the price has moved. 

Next step, we split the data as training and testing set. Then we created a new column called 'Prediction' by shifting 100 rows of 'close'.

In the next step, we are creating training data for x and y.

80% of training data will go to the variable called x_train
20% of training data will go to the variable called x_test

80% of y will go to the variable called y_train
20% of y will go to the variable called y_test

Now we start with the Regression Models

## Linear Regression Model
