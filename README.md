# Weather API Streamlit

A simple weather application built using Python and Streamlit. The application uses the Open-Meteo API to fetch current weather information for a selected city.

## Features

- Search weather by city name
- Displays current temperature
- Displays relative humidity
- Displays wind speed
- Uses real-time weather data
- Simple and user-friendly Streamlit interface

## Technologies Used

- Python
- Streamlit
- Requests
- Open-Meteo API

## API Used

This project uses the Open-Meteo API for weather information.

The application uses two API services:

1. Open-Meteo Geocoding API
   - Converts the city name into latitude and longitude.

2. Open-Meteo Forecast API
   - Uses latitude and longitude to retrieve current weather information.

## Project Structure

```text
weather-api-streamlit/
│
├── app.py
└── README.md
