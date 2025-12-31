# Weather App

A sleek desktop weather application built with **Python** and **PyQt5**.  
Enter a city name to get the **current temperature**, **weather description**, and an **emoji representation** of the weather.

![Weather App Preview](WEATHER-APP-PREVIEW.mp4)

________________________________

## Features
- Fetches real-time weather data using the **OpenWeatherMap API**
- Clean, modern, dark-themed UI with spacing and hierarchy
- Displays temperature, weather emoji, and description
- Robust error handling:
  - Invalid city names
  - Connection issues
  - HTTP errors (400, 401, 404, 500, etc.)
- Responsive UI with button hover effect

________________________________

## Installation / Steps

Follow these steps to run the app on your computer:

1. **Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/Weather-App.git
cd Weather-App

2. Create a virtual environment

python -m venv .venv

3. Activate the virtual environment

-Windows:
	.venv\Scripts\activate

-Mac/Linux:
	source .venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

5. Run the app

python WeatherApp.py

________________________________

Usage:

1. Launch the app

2. Enter a city name in the input field

3. Click Get Weather

4. View the temperature, weather emoji, and description

________________________________

Dependencies:

PyQt5
requests

________________________________

Notes:

Replace the API key in WeatherApp.py with your own OpenWeatherMap API key:

	api_key = "YOUR_API_KEY_HERE"

The app has a dark-themed UI with modern spacing, fonts, and hierarchy.