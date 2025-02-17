# Flight Price Prediction

## __Project Overview__

This project aims to predict flight ticket prices based on various factors such as airline, departure time, number of stops, and more. A Random Forest Regressor is used to develop a model that accurately estimates flight ticket prices by analyzing historical data.

## __Key Features__


* __Data Preprocessing__: Encoded categorical features.
* __Exploratory Data Analysis (EDA)__: Visualized feature correlations and analyzed important factors affecting flight prices.
* __Machine Learning Model__: Implemented a Random Forest Regressor for price prediction.
* __Performance Evaluation__: Measured model accuracy using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
* __Visualization__: Created a scatter plot to compare actual vs predicted flight prices, providing a visual representation of model accuracy.
* __Final Submission__: Generated predictions and formatted them for submission.


## __Dataset__

The dataset includes flight details from March to June 2019 in India, covering:

* __ID__: A sequential number assigned to each flight record.
* __Airline__: The name of the airline operating the flight.
* __Flight__: A unique identifier for each flight.
* __Source City__: The city from which the flight departs.
* __Departure Time__: The time at which the flight departs.
* __Stop__: The number of stops made during the flight.
* __Arrival Time__: The time at which the flight arrives at its destination.
* __Destination City__: The city where the flight is headed.
* __Class__: The class of service (e.g., economy, business, etc.) that the passenger chooses.
* __Duration__: The total flight duration from departure to arrival.
* __Days Left__: The number of days remaining until the flight departs.

## __Technologies Used__

* __Python__
* __Pandas & NumPy__ – Data manipulation
* __Matplotlib & Seaborn__ – Data visualization
* __Scikit-learn__ – Machine learning & model evaluation

## __Model Performance__

* __Mean Absolute Error (MAE)__: 2066.37
* __Mean Squared Error (MSE)__: 15,484,335.83
* __Root Mean Squared Error (RMSE)__: 3935.01
* __R² Score__: 0.9705
