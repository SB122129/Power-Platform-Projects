
# Weather App Custom Page in Power Apps

## Overview
**Weather App** is a custom page built using Power Apps that allows users to search for a city and view its current weather details. The app leverages a **custom connector** to fetch real-time weather data from the [WeatherAPI](https://www.weatherapi.com/). Users simply type in a city name into the search box, and the app displays various weather parameters including temperature, humidity, wind speed, and more.

## Features
- **City Search:** Quickly search for any city to retrieve its weather data.
- **Real-time Weather Data:** Display current weather conditions fetched live from WeatherAPI.
- **Custom Connector Integration:** Seamlessly integrates with WeatherAPI using a custom connector that accepts a city name as a parameter and returns detailed weather information.

## Screenshots
### App UI
*Below is a screenshot of the app's user interface:*

![WeatherappScreenshot](https://github.com/user-attachments/assets/b8f3e69c-3be4-4264-ad3e-760a4e24ab01)


### Custom Connector Definition
*Below is a screenshot showing the custom connector definition used to fetch weather data from WeatherAPI:*

![Screenshot_7-2-2025_162318_make powerapps com](https://github.com/user-attachments/assets/ebed73c6-7426-419a-8fe9-c5b2041ec1bf)


## Architecture
The application is developed as a **custom page** in Power Apps. The key components include:

- **Power Apps Custom Page:** Provides the user interface for entering a city name and displaying weather details.
- **Custom Connector:** Interfaces with WeatherAPI. It takes a city name as input and returns a JSON payload containing comprehensive weather information.
- **Related Data Sources:** The custom connector is configured to handle the API calls and integrates directly with the custom page for a seamless user experience.


## Custom Connector Details
The custom connector is configured to call the WeatherAPI service. It accepts a city name as a parameter and returns all weather data for that city. This modular design makes it easy to maintain and update the connector if the API changes. For detailed settings, refer to the custom connector screenshot above.



## Contact
For questions, feedback, or issues, please open an issue in this repository or contact [samiberhanu12@gmail.com](mailto:samiberhanu12@gmail.com).
