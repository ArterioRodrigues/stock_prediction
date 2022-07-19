# Data Mining Stock

### Table of Contents

1. [Description](#description)
2. [Preview](#preview)
3. [Technologies](#technologies)

## Description
-LSTM Model

The model was built on MSFT stock closing data being
at the year 2000-01-01. 80% of the data was used to predict the
next 20%
<br/>
To Build an LSTM models you need
-data set - Dataset is a 2d array [[60][60][60] … [60]]
-training set - is a 2d array [[60]]
The data set is use to
predict the training set. The model is trained until a loss
Limit is reached
<br/>
-How to use the Models
Our LSTM model can now be used to predict stock market closing prices based on
given data.
Restrictions:

- The given data must be in the same format as training data ie [[60] [60]....[60]]
- Has to be scaled between 1-0
- Data used has to be around the range of the training model The model will prediction a value based on the training based on MSFT


### Technologies
