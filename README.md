# OrthRNN

Four files will be uploaded into this repo. They are combinations of two types of RNN (original vs orthogonalized) and two types of tasks (NLP vs time-series forecasting)

The file currently residing in this repo is the implemtation of orginal RNN for time-series forcasting task. The main difference between it and the correpsonding orthgonalized verions is the orthogonalization function in the sdg function in the rnn class is commented out. If you delete the comment symbols, this model will behave the same as orthogonalized RNN.
