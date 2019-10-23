# Time-Series-Forecasting-using-RNN

BACKGROUND: 
This project was part of my online course. For this project, python, Keras, pandas, numpy , matplotlib has been used.

PROBLEM STATEMENT:
The objective was to predict Google's stock price.

DATA:
There are six features namely Date, Open, High, Low, Close, Volume. I have used the only Date and open.


APPROACH: 
First of all, feature scaling was needed. After that 60 timestamp which was necessary for sequence data.
after that, while using keras, sequential, dense, LSTM, dropout was imported. in the first layer, 50 units were used with 0.2 dropouts and the same for second, third and fourth layers. while compiling optimization Adam with loss function MSE was used.

SOLUTION: 
while fitting the RNN, the batch size was 32 and epoch 20 was used.  

RESULTS: 
mean squared error on test data was 42.17
