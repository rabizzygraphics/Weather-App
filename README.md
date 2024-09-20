# Weather App

The Weather App is a simple and interactive tool for checking real-time weather conditions in any city. Users can search for cities to view essential weather data such as temperature, humidity, and wind speed. The app also displays dynamic icons based on current weather conditions (e.g., rain, clouds, clear sky).

## Features

- **Real-time Weather Data**: Fetches live weather information for any city using the OpenWeatherMap API.
- **Search Functionality**: Users can search for any city to get the current weather conditions.
- **Weather Details**: Displays temperature, humidity, wind speed, and weather conditions.
- **Error Handling**: Displays an error message if an invalid city name is entered.
- **Dynamic Weather Icons**: Changes weather icons based on the current weather (e.g., rain, clouds, mist).

## Technologies Used

- **HTML**: Provides the structure and layout of the app.
- **CSS**: Used for styling and creating a responsive design.
- **JavaScript**: Handles the logic of fetching and displaying weather data using the OpenWeatherMap API.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/rabizzygraphics/weather-app.git
   ```

2. Navigate to the project folder:

   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your browser.

4. Enter the name of a city in the search bar and click the search button to view the current weather conditions for that location.

## Project Structure

```bash
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
├── images/             # Icons for different weather conditions
├── script.js           # JavaScript file for weather logic
└── README.md           # This file
```

## API Used

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. The `apiKey` is included in the JavaScript for demonstration purposes. Make sure to replace it with your own API key if you deploy the app.

## Screenshots

![Weather App Screenshot](screenshot.png)

## Future Improvements

- **Add a 5-day weather forecast.**
- **Implement geolocation for automatic weather updates based on the user’s location.**

## License

This project is licensed under the MIT License.
