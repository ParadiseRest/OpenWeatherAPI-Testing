# OpenWeather API Testing Project

This project showcases API testing using Postman on the OpenWeather API. The project includes automated tests to validate weather data retrieval for a given city, 5-day weather forecast, and error handling for invalid city names.

## Project Structure:
- `OpenWeatherAPI_Postman_Collection.json`: The Postman collection for OpenWeather API endpoints.
- `postman_tests.js`: JavaScript file containing the Postman tests.
- `api_test_results.md`: Detailed test results of the API testing process.

## How to Use:
1. Import `OpenWeatherAPI_Postman_Collection.json` into Postman.
2. Add your API Key to the Postman environment (`API_KEY`).
3. Run the collection to test the API and review the test results.

## Endpoints Covered:
1. **Current Weather Data**: Retrieves current weather data for a city.
2. **5 Day Forecast**: Provides a 5-day weather forecast.
3. **Invalid City Test**: Tests for invalid city error handling.

## Test Cases:
- Validate HTTP status codes.
- Check JSON response structure.
- Ensure the correct data is returned (city name, temperature, etc.).
# OpenWeatherAPI-Testing
