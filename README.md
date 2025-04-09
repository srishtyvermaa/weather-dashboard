Weather Dashboard
A responsive web application that allows users to search for any city and view its live weather information, including temperature, weather conditions, humidity, and wind speed. Built using React.js and integrated with the OpenWeatherMap API.

Tech Stack
Frontend Framework: React.js

HTTP Client: Axios

Styling: Tailwind CSS

State Management: React Hooks

Deployment Platform: Vercel

Features
Search Functionality:

Users can search for any city to view live weather information.

Weather Information Display:

City Name

Current Temperature (°C)

Weather Condition (e.g., Sunny, Rainy)

Humidity (%)

Wind Speed (km/h)

Weather Icon

Error Handling:

Displays user-friendly error messages for invalid city names or API failures.

Loading State:

Shows a loading animation while fetching data.

Responsive Design:

Optimized for both mobile and desktop screens.

Setup Instructions
Follow these steps to run the project locally:

Clone the repository:

bash
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
Install dependencies:

bash
npm install
Create a .env file in the root directory and add your OpenWeatherMap API key:

text
REACT_APP_WEATHER_API_KEY=your_api_key_here
Start the development server:

bash
npm start
Open your browser and navigate to:

text
http://localhost:3000
API Integration
API Used: OpenWeatherMap Current Weather API

Endpoint Example:

text
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
Replace {city} with the name of the city and {API_KEY} with your API key.

Rate Limits: Free tier allows up to 60 requests per minute.
