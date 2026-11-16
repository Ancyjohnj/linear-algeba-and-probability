#Building a SimpleRNN Model for Weather Temperature Prediction#

#Project Description

This project uses a SimpleRNN deep learning model to predict daily temperature using historical weather data.

#Dataset

#DailyDelhiClimate Dataset

#The dataset contains:

.Date

.Mean Temperature

.Humidity

.Wind Speed

.Mean Pressure

#Technologies Used

.Python

.Pandas

.NumPy

.Matplotlib

.Scikit-learn

.TensorFlow / Keras

Jupyter Notebook

#Data Preprocessing

.Loaded the weather dataset.

.Checked missing values.

.Converted the date column into datetime format.

.Sorted the data by date.

.Selected temperature, humidity, and wind speed as input features.

.Applied MinMaxScaler.

.Created sequences using the previous 7 days.

#Model Architecture

.SimpleRNN with 64 units

.Dropout layer (0.2)

.Dense output layer

#Model Training

.Optimizer: Adam

.Loss Function: Mean Squared Error (MSE)

.Metric: Mean Absolute Error (MAE)

.Epochs: 50

.Batch Size: 32

##Model Evaluation

#Metric

.RMSE 2.11 °C

.MAE 1.73 °C

.R² Score 0.8922

##7-Day Temperature Forecast

Day Predicted Temperature

Day 1 30.71 °C

Day 2 29.29 °C

Day 3 28.29 °C

Day 4 27.39 °C

Day 5 26.63 °C

Day 6 26.04 °C

Day 7 25.50 °C

##Note: Future humidity and wind speed values were carried forward from the last available input row during recursive forecasting.

#Output Files

.SimpleRNN_Weather_Prediction.ipynb

.simple_rnn_weather_model.keras

.next_7_days_forecast.csv

.README.md

#Conclusion

The SimpleRNN model was successfully trained to predict daily temperature using historical weather data. The model achieved an R² score of 0.8922 and generated a 7-day temperature forecast.

Name:Ancy john j
