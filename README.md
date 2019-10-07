# Learn-Alphabets-LSTM
LSTMs learning alphabets in different ways 

1. one_char to one_char --
Naive LSTM learning one char to one char with no dependencies and achieved an accuracy of 100%.

2. one_char to one_char state --
An LSTM learning alphabets sequence with state maintained within a batch and achieved an accuracy of 100%.

3. feature window to one_char --
An LSTM learning alphabets with a feature size and 1 time step and achieved an accuracy of 86.96%.

4. time steps window to one_char --
An LSTM learning alphabets with some time steps and 1 feature step and achieved an accuracy of 100%.

5. Var length input to one char -- 
An LSTM learning alphabet sequences with variable length and outputs one character and achieved an accuracy of 
