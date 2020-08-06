AQI Prediction

Problem Statement: We try to predict PM2.5 AQI of Beijing with climatic conditions as independent variables. We take data from 2010 to 2014.

Data Preparation: We get raw climatic data from: https://en.tutiempo.net/climate/ through web scraping. 
		  PM2.5 AQI Data is obtained from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data

Modeling: We have used different machine learning models and ANN architectures in order to determine which model gives the least mse. 

Tuned Random Forest model is available in the directory as a pickle file.