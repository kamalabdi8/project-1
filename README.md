# Weather App

## Overview

This weather app fetches weather data from the OpenWeatherMap API based on user input. The app displays city name, country flag, temperature, weather description, cloud percentage, humidity, and pressure. When you start the app, it defaults to showing the weather in *Kampala*.

## Features

- Search for weather by city name.
- Displays weather information such as temperature, weather condition, cloud coverage, humidity, and pressure.
- Shows country flags based on the city location.
- Error handling when a city is not found.
- Default city weather is displayed when the app starts.

## Technologies

- *HTML5*: Structuring the webpage.
- *CSS3*: Styling the application.
- *JavaScript*: Fetching weather data from the API and updating the DOM.
- *OpenWeatherMap API*: Provides real-time weather data.
- *FontAwesome*: For icons used in weather details.

## Files

- index.html: The main HTML file that structures the app.
- style.css: The stylesheet for the app, providing styling and layout.
- index.js: Contains the JavaScript logic to fetch weather data and update the interface.
- db.json: Simulated weather data for testing purposes.
- README.md: Project documentation (this file).

## How to Run

### Prerequisites

You need a web browser and internet access to retrieve data from the OpenWeatherMap API.

### Instructions

1. Clone this repository to your local machine.
2. Open the index.html file in a browser to see the app in action.
3. You can search for any city name in the input field and press the search button to fetch the weather data.
4. The app displays temperature, weather conditions, humidity, pressure, and cloudiness percentage of the selected city.

### API Key

To use live weather data, replace the id variable in index.js with your OpenWeatherMap API key.

```js
let id = 'MY_API_KEY';# project-1
