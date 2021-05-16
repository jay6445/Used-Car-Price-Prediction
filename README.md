# Used-Car-Price-Prediction

Prices of used cars need to be predicted based on their condition. A dataset of past sales has been provided which can be used to train the machine learning model. The dataset is available at https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data.

The dataset column headers are available seperately at https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.names

**Cleaning** 
The records that do not have price values are droped.

**Normalization** 
Data is normalized by dividing the columns by max value to bring them in the same range to make inferences easier.

**Statistics**
Correlation is calculated between all the columns to observe any strong correlation that exists.

**Descriptive Analytics**
Descriptive Analytics is used to visualize the resulting correlations using heatmap.

**Predictive Analytics**
Linear Regression model is built using Ordinary Least Squared Estimates.

The regressor obtained is then evaluated for accuracy based on parameters like the p-value and adjusted R squared.

The model built is then tested and the predicted prices obtained are compared to the actual prices by ploting the distribution.








