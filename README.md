Overview
This project provides weather forecasting by utilizing real-time data from OpenWeatherMap API and historical weather data. It uses machine learning models to predict future temperature, humidity, and rain probabilities.

Features
Fetches current weather data for a given city using OpenWeatherMap API.

Reads and processes historical weather data from a CSV file.

Uses machine learning models (Random Forest) to predict rain probability.

Implements regression models to forecast future temperature and humidity.

Requirements

Install the necessary dependencies using:
pip install requests pandas numpy scikit-learn pytz

Run the script and enter a city name when prompted:
python weatherforcast.py

How It Works
1)Fetching Current Weather:
Uses OpenWeatherMap API to get real-time weather data.

2)Processing Historical Data:
Reads weather data from a CSV file.

Encodes categorical variables.

3)Machine Learning Models:
Rain Prediction: Uses Random Forest Classifier.

Temperature & Humidity Forecast: Uses Random Forest Regressor.

4)Displaying Forecast:
Shows current weather conditions.

Predicts rain probability.

Provides hourly temperature and humidity forecasts.

API Key
Replace API_KEY in the script with your OpenWeatherMap API key.

Notes
Ensure the historical data file (weather.csv) is present in the correct path.

Modify the timezone setting as needed in weather_view().

License
This project is for educational and personal use only.


