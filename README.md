# ptsa2019project
Project about Residual Recurrent Neural Networks


### Shreyas - 11/14/2019
Progress so far

Read through the paper fully

Got climate data (ENSO: 2 datasets Nino 3.4 and Nino1.2) that is used in the paper. Got it formatted right as well

Tried fitting ARIMA model as in the paper. Model fit very well. much better than the paper. Not sure
where i am going wrong here. paper is also not clear at a few places

paper does not mention
1. if results are on test or val for ENSO
2. which lag they finally used
3. if/how they used regularization in arima
4. mean is subtracted from training data. but how to rescale predictions? adding
means to predicted data is giving near perfect results

insights for both datasets are same

Tried RNN model using LSTM. Able to train a model and see some result. but lots of debugging still left
used code from https://towardsdatascience.com/lstm-for-time-series-prediction-de8aeb26f2ca#:~:targetText=The%20idea%20of%20using%20a,looking%20only%20at%20its%20past.
