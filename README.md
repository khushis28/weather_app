# Weather App 🌤️
A modern, responsive weather application that provides real-time weather information for any city worldwide. Built with vanilla HTML, CSS, and JavaScript, featuring a beautiful gradient design and intuitive user interface.

# Features
Real-time Weather Data: Get current weather information using OpenWeatherMap API
City Search: Search for weather information by city name
Dynamic Weather Icons: Visual weather representations that change based on conditions
Responsive Design: Works seamlessly on desktop and mobile devices
Error Handling: User-friendly error messages for invalid city names
Weather Details: Displays temperature, humidity, and wind speed
Modern UI: Clean gradient design with smooth animations

# Screenshots
The app features a beautiful gradient card interface with:
![image](https://github.com/user-attachments/assets/7cbd4301-e389-443f-9d68-a8aeccec665a)

Clean search input with search button
Large weather icons for visual appeal
Temperature display in Celsius
Humidity and wind speed indicators
Error handling for invalid searches

# Technologies Used
HTML5: Semantic markup structure
CSS3: Modern styling with gradients and flexbox
JavaScript (ES6+): Async/await for API calls and DOM manipulation
OpenWeatherMap API: Real-time weather data
Google Fonts: Poppins font family for typography

# Installation
Clone the repository:
## bash ##
git clone https://github.com/username/weather-app.git
cd weather-app

Get your API key from OpenWeatherMap:
Sign up for a free account
Generate your API key
Replace the apiKey variable in the JavaScript code with your key

# Set up the project structure:
weather-app/
├── index.html
├── style.css
├── README.md
└── images/
    ├── search.png
    ├── rain.png
    ├── clouds.png
    ├── clear.png
    ├── drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png
Add the required weather icons to the images/ folder
Open index.html in your web browser or serve it using a local server

# Usage
Enter a city name in the search input field
Click the search button or press Enter


# View the current weather information including:
Current temperature
Weather condition with icon
Humidity percentage
Wind speed

# API Configuration
The app uses the OpenWeatherMap API. To set up:
Replace the apiKey variable with your actual API key:
javascript
const apiKey = "your-api-key-here";
The API endpoint used:
javascript
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?&units=metric&q=";
Weather Conditions Supported

# The app displays different icons for various weather conditions:

☀️ Clear sky
☁️ Cloudy
🌧️ Rain
🌦️ Drizzle
🌫️ Mist/Fog

# CSS Features
Gradient Background: Beautiful linear gradient from teal to purple
Responsive Design: Adapts to different screen sizes
Modern Typography: Uses Poppins font family
Smooth Animations: Hover effects and transitions
Flexbox Layout: Efficient and responsive layout system
JavaScript Functionality
Async API Calls: Uses modern async/await syntax
Error Handling: Graceful handling of invalid city names
DOM Manipulation: Dynamic content updates
Event Listeners: Interactive search functionality

# Browser Compatibility
Chrome (recommended)
Firefox
Safari
Edge
Mobile browsers
Contributing

# Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

# Acknowledgments
OpenWeatherMap for providing the weather API
Google Fonts for the Poppins font family
Weather icons (please add attribution for your icon source)
Contact
Project Link: [https://github.com/username/weather-app](https://github.com/khushis28/weather_app/new/main?filename=README.md)

⭐ Star this repository if you found it helpful!

