# Weather-App
This is a simple weather application built using React and Axios. It allows users to check the current weather of any city by entering the city name. The app fetches real-time weather data from the OpenWeatherMap API and displays essential information such as temperature, weather description, and wind speed.

# Features
Real-Time Weather Data: Fetches current weather information from the OpenWeatherMap API.

City Search: Users can input any city name to get the weather details.

Error Handling: Displays an error message if the city is not found or the input is empty.

Responsive Design: Utilizes Tailwind CSS for a clean and responsive user interface.

# Technologies Used
React: JavaScript library for building user interfaces.

Axios: Promise-based HTTP client for making requests to the OpenWeatherMap API.

Tailwind CSS: Utility-first CSS framework for styling.

OpenWeatherMap API: Provides weather data.

# Installation
Prerequisites
Ensure you have the following installed:

Node.js (v14 or higher)

npm (v6 or higher)

Steps
Clone the repository:

bash

git clone https://github.com/your-username/weather-app.git
cd weather-app
Install dependencies:

bash

npm install
Create a .env file in the root directory and add your OpenWeatherMap API key:

env

REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
Start the development server:

bash

npm start
Open your browser and navigate to http://localhost:3000 to view the app.

# Usage
Upon launching the app, enter a city name in the input field and click the "Get Weather" button to retrieve the current weather information, including:

Temperature (°C)

Weather description

Wind speed (m/s)

If the city is not found or the input is empty, an error message will be displayed.
