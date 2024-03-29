# Predicting the Federal Election of Germany
Machine Learning project to predict vote shares outcome in a multiparty election system

#### Abstract

Forecasting in social science is a complicated business with questionable outcomes. Despite this, predicting the result of a democratic election has witnessed growing popularity, especially since the 2016 United States presidential election, which defied almost all major projection efforts. Forecasting elections is quite different from other types of political science studies as it is driven mainly by data and the goal is to make accurate predictions, but not to interpret their results.

The goal of this paper is to test whether it is possible to predict election outcome in Germany, where a wide range of parties are competing for power, utilizing current algorithms from machine learning and deep learning methodologies, which are not commonly employed for predicting multiparty systems. The complex federal parliamentary republic system of Germany provides a compelling contrast to the two-party system of the United States and thus will add greater depth to this field of research.

The models implemented in this paper build upon the work done by Stoetzer et al. (2019). This project will expand further on their analysis by investigating whether approaches using machine learning and neural networks will improve upon their existing methodology.

#### Methodology

Existing literature that endeavors to forecast election results have largely been based on classical statistical mod- elling with a multitude of assumptions about how the system works. Machine learning and deep learning models, on the other hand, do not require as many assumptions about the relationships between the variables of interest. Therefore, our research will seek to discover how well machine learning and deep learning forecasting could perform compared to existing statistical models when using the same data.
This project will employ three approaches to determine which model has the best predictive ability:
<ol>
<li> Traditional machine learning regression algorithms: this will use simple model set-up with training and test set data to predict party vote shares on election day;
</li>
<li> Deep Neural Network (DNN) with different layers of learning: this model will utilize different optimizers and automate the process of searching for the best hyperparameters to find the most appropriate set-up for this time-series problem;
</li>
<li> Recurrent Neural Network (RNN) and Long Short-Term Memory(LSTM) units: as time series data are temporal, the most appropriate methodology may be a sequence model, such as RNN and LSTM units. The state vector and the cell state in these models will allow us to maintain context across a series. With time series data, the closer the data point is to the predic- tion date, the bigger impact it will have on the final outcome. For this data set, the closer a poll is to an election day, the more powerful its predictive ability will be. Stoetzer et al. (2019) account for by this using the backward random-walk technique, therefore, it is necessary to similarly weight the polling data in the machine learning model. By using RNNs and LSTMs, this project can similarly carry context from close to far away by using cell state that retains this information through a long learning process.
</li>
</ol>	

![alt text](https://github.com/huydang90/Predicting-German-Election/blob/master/Progress%20Report/Predict%20German%20Election%20Poster.png?raw=true)


