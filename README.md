# Weather Information App

## Overview
The Weather Information App is a JavaFX-based application that fetches and displays real-time weather data using the OpenWeatherMap API. Users can enter a city name to retrieve weather details such as temperature, humidity, and weather conditions, along with a weather icon representing the current condition.

## Features
- **API Integration**: Fetches real-time weather data from OpenWeatherMap.
- **User-friendly GUI**: Built with JavaFX for a smooth user experience.
- **Weather Icon Display**: Shows the correct weather condition icon dynamically.
- **Unit Conversion**: Supports both Celsius and Fahrenheit.
- **Search History**: Keeps track of recent searches.
- **Error Handling**: Alerts for invalid city names and API failures.

## Installation & Setup
### Prerequisites
- Java Development Kit (JDK) 8 or later
- JavaFX Library
- An OpenWeatherMap API Key

### Steps to Run the Application
1. Clone or download the source code.
2. Open the project in an IDE (e.g., IntelliJ, Eclipse, NetBeans).
3. Ensure JavaFX libraries are properly configured.
4. Replace `YOUR_API_KEY` in the source code with your actual OpenWeatherMap API key.
5. Compile and run the `WeatherApp.java` file.

## API Integration
The application makes use of OpenWeatherMap’s API:
- **Current Weather Data**: `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units={unit}`
- **Weather Icons**: `https://openweathermap.org/img/wn/{icon}@2x.png`

## How to Use
1. Enter the city name in the text field.
2. Select temperature unit (Celsius/Fahrenheit).
3. Click the **Get Weather** button.
4. View the weather details and icon.
5. Check search history for past queries.

## Error Handling
- If an invalid city is entered, an error message is displayed.
- If there is a network or API failure, an alert notifies the user.

## License
This project is for educational purposes and free to use.

## Author
[Your Name]

# WeatherAppJavaFX
