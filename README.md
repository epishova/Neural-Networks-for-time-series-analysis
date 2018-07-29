# Neural-Networks-for-time-series-analysis

### Compare how ANNs, RNNs, LSTMs, and LSTMs with attention perform on time-series analysis

In this project, I build and compare four types of ANN models: fully connected ANN, RNN, LSTM,
LSTM with Attention. There are two datasets which contain time series. The goal is to build deep neural networks which can
learn the temporal patterns in data and predict a value of future observation. For those models, I compare the accuracy of
predictions and the speed of the training process. Please refer to `Report.pdf` for detailed description and references.

To build the neural networks I use python `keras` library. To implement Attention Mechanism I used the [source code](https://gist.github.com/cbaziotis/6428df359af27d58078ca5ed9792bd6d) of Christos Baziotis.
