# Weather App
### Overview
A simple weather application that fetches real-time weather data from the OpenWeather API and displays it dynamically.
Users can search for a city to get the current temperature, humidity, wind speed and weather conditions with an 
adaptive background.

### Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeather API

### Getting Started
Prerequisites: 
- A web browser
- A text editor (eg VSCode)

Installation: 
1. Clone the repository
2. Navigate to the project folder
3. Open the project with LiveServer in VSCode or open index.html directly in a browser

API Key: 
This app uses the OpenWeather API. You need an API key to fetch weather data. 
1. Sign up at OpenWeather to get a free API key
2. Replace the apikey value in the script inside index.html  (const apiKey = "your-api-key-here";)

### Usage
1. Enter a city name in the search box
2. Click the search button or press the enter key
3. The app will display:
- Temperature in Celsius
- Humidity percentage
- Wind speed in km/h
- Weather condition icon
- Adaptive background colours based on weather condition
4. If an invalid city is entered, an error message will be shown

### Future Improvements
- Multiple language support
- Temperature unit toggle between Celsius and Farenheit
- Animations & UI improvements
- Extended forecast
- Alternative weather APIs as fallback incase OpenWeather is unavailable

### Acknowledgements
- OpenWeather API
- Icons from OpenWeather
