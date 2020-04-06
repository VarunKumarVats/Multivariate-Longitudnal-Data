# Multivariate-Longitudnal-Data

This project aims at developing counterfeit models to predict energy consumption of buildings considering following factors :

1. Building Details : floor count, square feet, year built and type of building (residential, education, office, parking, etc.)
2. Weather Details :  air temperature, dew temperature, sea level pressure, wind direction and wind speed

In this project, energy consumption was obtained using three different approaches. These approaches include:

1. Boosting Methods : The Boosting algorithms used for prediction includes Gradient Boosting (LightGBM) and Cat Boost.
2. Lagging Methods : The Lagging (time-shift) is being done on original dataset to observe trend provided by the dataset  and prediction is provided using Boosting Methods.
3. Deep Learning and Neural Network: The Neural Network (Fully Connected) and Deep Learning (RNN and CNN) models are used for prediction based on sequence being followed by original data.

Finally, regression metrices used in this project are as follows:

1. Root Mean Square Error (RMSE)
2. Mean Absolute Error (MAE)
3. Mean Absolute Percentage Error (MAPE)

