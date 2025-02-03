Weather App

Overview:
This project is a simple weather application that allows users to search for a city's weather details using the OpenWeatherMap API. The app displays current weather conditions, temperature, wind speed, humidity, and pressure. It also provides options to switch between Celsius and Fahrenheit.

Features:

Search for a city's weather.

Display current temperature, min/max temperature, humidity, wind speed, and pressure.

Show country code and country name alongside the city name.

Fix function to properly handle timezone conversion and unit switching.

Switch between Celsius and Fahrenheit.

Responsive design for different screen sizes.

Technologies Used:

HTML

CSS

JavaScript

OpenWeatherMap API

Running the Project Locally:

Prerequisites:

A web browser (Chrome, Firefox, Edge, etc.)

An internet connection

Steps:

Clone this repository or download the project files.

Navigate to the project directory.

Open the index.html file in a web browser.

The application should now be running and ready to use.

Approach and Challenges Faced:

Approach:

Fetching Weather Data: Used JavaScript fetch API to retrieve weather data from OpenWeatherMap.

Dynamic Updates: Utilized DOM manipulation to update weather details dynamically.

Country Code & Name: Implemented a function to display the country code and full country name alongside the city.

Function Fixes: Fixed issues with timezone conversion and unit switching to ensure accurate data display.

Responsive Design: Styled using CSS to ensure a smooth experience across different screen sizes.

Challenges & Solutions:

API Integration Issues: Encountered minor issues while fetching data due to incorrect API key usage. Resolved by verifying the API key and request URL.

Timezone Display: The weather API provides timestamps in UTC, which required conversion using JavaScript's Date object.

UI Consistency: Adjusted styles for different screen sizes using media queries to improve mobile usability.

Country Code & Name: Added a feature to fetch and display the correct country code and name for better clarity.

Fixed Function: Debugged and improved the function to ensure accurate temperature and timezone handling.