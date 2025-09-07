# PRODIGY_WD_05

# Weather App

A simple, clean, and responsive web application that fetches and displays the current weather for any searched city using the [OpenWeatherMap API](https://openweathermap.org/api).

## Features

- Search weather information by city name.
- Displays city, date, current temperature, weather condition, and high/low temperature.
- Clean UI inspired by popular minimalist weather apps.
- Real-time fetching of weather data from OpenWeatherMap API.

## Demo

Open `index.html` in a browser and try typing city names in the search box.

## Usage

### Setup

1. Clone or download this repository.
2. Replace the API key in `main.js` with your own from [OpenWeatherMap](https://openweathermap.org/api).

const api = {
key: "YOUR_API_KEY_HERE",
base: "https://api.openweathermap.org/data/2.5/"
}

3. Open `index.html` in any modern browser.

### How it works

- Enter a city name and press **Enter**.
- The app fetches weather data from OpenWeatherMap.
- Displays:
- City and country
- Current date
- Temperature (°C)
- Weather description (e.g., Sunny, Rain)
- High / Low temperatures

## File Structure

├── index.html # Main HTML structure

├── main.css # Stylesheet for UI styling

├── main.js # JavaScript to handle API calls and UI updates


## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap API

## API Key

This application requires a valid OpenWeatherMap API key to fetch weather data. To obtain an API key:

- Sign up at https://openweathermap.org/
- Navigate to your profile > API keys
- Generate and copy your API key
- Replace `"YOUR_API_KEY_HERE"` in `main.js` with your key

## License

This project is provided for educational purposes and is free to use and modify.

---

Feel free to enhance this app by adding user location detection, extended forecasts, or more detailed weather data. Pull requests and suggestions are welcome!
