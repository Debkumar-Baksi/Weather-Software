# 🌦️ Weather App

## 📜 Description

This **Weather App** is a Python application built using Tkinter and OpenWeather API that provides real-time weather information. The app allows users to search for weather details by entering a city name, and it displays the current temperature, weather condition, humidity, pressure, wind speed, and description.

---

## ✨ Features

- **Real-time Weather Updates**: Get the current weather of any city in real time.
- **User-friendly Interface**: Simple and intuitive interface built with Tkinter.
- **Detailed Weather Information**: Displays temperature, humidity, wind speed, pressure, and weather description.
- **Time Zone**: Shows the local time of the city based on its geographical location.

---

## 🛠️ Requirements

- Python 3.x
- `Tkinter` library (for creating the GUI)
- `requests` library (for fetching weather data from the API)
- `geopy` library (for location-based timezone conversion)
- `timezonefinder` library (to determine the timezone of the city)
- `pytz` library (for handling timezone conversions)

To install the required libraries, run the following commands:

```bash
pip install requests
pip install geopy
pip install timezonefinder
pip install pytz
```
## 🖥️ How to Run
- **Prerequisites**: Ensure Python and the required libraries are installed.

- **Run the Script**:

  - Save the code to a file, for example, weather_app.py.
  - Open a terminal/command prompt and navigate to the directory containing the script.
  - Run the script using the following command:
```bash
python weather_app.py
```
- **Enter a City Name**:

  - Type the name of the city in the search box and press the search button to fetch weather details.
## 🛠️ Code Overview
- **Imports**
  - Tkinter: A Python library for creating graphical user interfaces.
  - geopy: A library for geocoding and retrieving location data.
  - timezonefinder: Used to get the timezone of a location.
  - requests: Used to make HTTP requests to the OpenWeather API.
  - pytz: A library for handling time zone conversions.
- **Steps in the Script**
- City Search:

  - User inputs a city name, and the app fetches the weather data for that city.
- Weather Data:

  - The app makes an API call to the OpenWeather API using the city name.
  - It retrieves and displays data like temperature, weather condition, humidity, pressure, and wind speed.
- Timezone and Time:

  - Using the geopy and timezonefinder libraries, the app determines the local time zone of the city and displays the current time.
- GUI:

  - The app is built using Tkinter with a simple interface including labels, buttons, and images.
- Error Handling:

  - If an invalid city is entered or the API request fails, an error message is displayed.

## 📂 License
This project is licensed under the MIT License.

## 👤 Author
[Debkumar Baksi](https://www.linkedin.com/in/debkumar-baksi-269738279/) 
