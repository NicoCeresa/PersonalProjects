# Beijing Pollution Forecast

## Main Method
I used Long Short-Term Memory(LSTM) to forecast pollution levels of Beijing.

### What is LSTM?
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. The central role of an LSTM model is held by a memory cell known as a ‘cell state’ that maintains its state over time. The cell state is the horizontal line that runs through the top of the below diagram. It can be visualized as a conveyor belt through which information just flows, unchanged. Information can be added to or removed from the cell state in LSTM and is regulated by gates. These gates optionally let the information flow in and out of the cell. It contains a pointwise multiplication operation and a sigmoid neural net layer that assist the mechanism.

## Other methods used
Data cleaning, Feature Engineering, Data Scaling, Train-test split, Neural Network Building, analyzing loss(the penalty for a bad prediction), testing results using root mean squared error
