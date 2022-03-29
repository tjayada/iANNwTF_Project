The raw data folder contains the raw data we got from the competition at https://zindi.africa/competitions/zindiweekendz-learning-urban-air-pollution-challenge

The cleaned data (1) folder contains the data we have obtained after removing columns that mainly consisted of missing data.

The cleaned data (2) folder contains the data we have obtained by filling the missing data with the mean values of the respective columns.

Both cleaned data (1) and (2) are usable, but the models perform better on the first data (1) set, as we have found out. 

The cleaned data LSTM (1) is specially build for the LSTM model, since it also contain the encoded locations on top of the cleaned data (1).