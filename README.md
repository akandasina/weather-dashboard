# Weather Dashboard for Hoboken, NJ

This Python project fetches real-time weather data from the OpenWeatherMap API for Hoboken, NJ, and provides a 5-day weather forecast. It uses Python's `requests` library to interact with the API and `matplotlib` to visualize temperature changes over the forecast period.

## Features:
- Fetches and displays **current weather** including temperature, humidity, wind speed, and weather description.
- Shows **sunrise and sunset** times.
- Displays a **5-day forecast** with temperatures at 3-hour intervals.
- **Visualizes** temperature data in a line plot using `matplotlib`.

## Requirements:
- Python 3.x
- Libraries:
  - `requests`
  - `matplotlib`

## How to Run:
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install requests matplotlib

Run the script: python weather_dashboard.py

Example Output:
City: Hoboken
Temperature: 15°C
Humidity: 65%
Wind Speed: 5.2 m/s
Weather Description: clear sky
Sunrise: 2023-10-12 10:23:45
Sunset: 2023-10-12 19:02:12

5-Day Forecast:
2023-10-12 12:00:00 | Temp: 15°C
2023-10-12 15:00:00 | Temp: 16°C
2023-10-12 18:00:00 | Temp: 14°C
