# TIME-SERIES-FORECASTING-USING-NEURAL-NETWORK
RCNN deal with sequence of data(Time Series Forecasting) to predict the output,now we will try to predict stock price

# QUESTIONS<br>
<h3>1.why RCNN?</h3>
it deals with sequence of data and give better performance<br>
<h3>2.train and test data?</h3>
we take the first 60 days data as input and very next day data as output<br>

# STEP BY STEP<br>
1.load the data ,check the "null values"<br>
2.split the data into train,test<br>
3.Normalization should take place in data for better result<br>
4.get first 60 days data as "input" and next day data as "ouput"<br>
5.repeat the same step for test data <br>
6.create the neural network model with "RNN","SRNN","GRU"<br>
7.train and compile the model<br>

<h3>Reference</h3>
https://www.kaggle.com/faressayah/stock-market-analysis-prediction-using-lstm<br>
https://www.kaggle.com/pierpaolo28/stock-market-analysis-and-time-series-prediction
