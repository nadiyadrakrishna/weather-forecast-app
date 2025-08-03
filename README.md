Weather Forecast App
A dynamic web application that provides real-time weather and a 5-day forecast for any city or for your current location.

✨ Features
Current Weather: Displays temperature, humidity, wind speed, and a "feels like" temperature.

5-Day Forecast: Shows a multi-day forecast with daily highs, lows, and weather conditions.

Search by City: Allows users to search for weather data for a specific city.

Auto-Location: Provides weather information for the user's current location using geolocation.

Simple Caching: Implements an in-memory cache to reduce redundant API calls and improve performance.

Responsive Design: The user interface is built to be accessible and functional on both desktop and mobile devices.

🛠️ Technologies Used
Node.js: The backend runtime environment.

Express.js: A fast, unopinionated, minimalist web framework for Node.js.

EJS (Embedded JavaScript): A templating engine to generate HTML with dynamic data.

Axios: A promise-based HTTP client for making API requests.

OpenWeatherMap API: The data source for all weather and forecast information.

Dotenv: To manage environment variables and keep the API key secure.

🚀 Getting Started
Follow these steps to get a copy of the project up and running on your local machine.

Prerequisites
You will need to have Node.js and npm installed on your computer.

Installation
Clone the repository:

git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

Install NPM packages:

npm install

Set up your API Key:

Get an API key from OpenWeatherMap.

Create a file named .env in the root directory of your project.

Add your API key to the .env file like this:

WEATHER_API_KEY=YOUR_API_KEY_HERE

Important: Do not share this file or commit it to GitHub.

Run the application:

npm start

The application will now be running at http://localhost:3000.

🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📜 License
Distributed under the MIT License. See LICENSE for more information.