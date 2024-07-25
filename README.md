Name:PRISHA HAIRIYA

Company: CODTECH IT SOLUTIONS

ID: CT12DS1866

Domain: Web Developement

Duration: July to September 2024

Mentor: Neela Santhosh Kumar

OVERVIEW OF THE PROJECT

The provided code snippet is for a React application that fetches and displays current weather and a 5-day weather forecast for a specified city using the OpenWeatherMap API. Here's a brief overview:

Imports: The code imports necessary libraries and components, including React, Axios, Framer Motion for animations, weather icons from react-icons, and a loading spinner from react-loader-spinner.

State Variables: The application uses React hooks (useState, useEffect) to manage state variables such as weather, forecast, city, loading, and error.

API Key: An API key for OpenWeatherMap is specified.

Effect Hook: The useEffect hook triggers fetching of weather and forecast data whenever the city state changes.

Fetch Functions:

fetchWeather retrieves current weather data.
fetchForecast retrieves 5-day weather forecast data.
Both functions handle loading states and errors.
Additional functions fetch data based on geolocation coordinates.
Helper Functions:

updateBackground changes the background image based on weather conditions.
getWeatherIcon returns the appropriate weather icon.
getDayName converts date strings to day names.
Rendering:

Input fields for city name and buttons to fetch weather data.
Loader spinner during data fetching.
Display of weather data with animations and weather icons.
Display of 5-day weather forecast.
CSS: Styles include general layout, search box, buttons, weather details, and animations.

This application provides an interactive and visually appealing way to check the weather and forecast for any city.

![weather](https://github.com/user-attachments/assets/bb885a2f-27a4-4b2e-9807-1db65fcec42e)
