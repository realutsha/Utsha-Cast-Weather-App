UtshaCast Weather App
UtshaCast is a simple weather application made entirely on one web page. It lets you check the current weather conditions, including temperature, humidity, and wind speed, for any major city in the world. The project is built using modern client-side web technologies, making it lightweight and fast to load. The design uses a dark, striking theme with strong primary red accents for a professional and bold look. This single-file setup is ideal for quick deployment on platforms like GitHub Pages.
Key Features
●	Responsive Design: Works well on phones, tablets, and computers, adjusting its layout for all screen sizes.
●	Dynamic Search: You can search for weather data instantly by typing the city name.
●	Modern UI: Uses Tailwind CSS for a clean, dark-mode design that is consistent and easy to read.
●	Clear Metrics: Displays essential information like 'Feels Like' temperature, humidity, wind speed, and atmospheric pressure.
●	Client-Side Logic: All data fetching and screen updates are handled by the JavaScript code without needing a separate backend server.
💻 Technologies Used
●	HTML5: Provides the core structure and layout of the application.
●	Tailwind CSS: Used for all styling. This utility-first framework enables quick styling for a fully responsive and visually appealing interface, including the dark background and custom red color palette.
●	Vanilla JavaScript (ES6+): Manages all application logic, handles user interaction, processes the raw data from the external API, and dynamically updates the elements on the page.
●	Fetch API: The built-in browser tool used to make asynchronous network requests to the weather service.
🛠️ Setup and Usage
This project uses standard web files (HTML/CSS/JS) and does not need a server to run.
1.	Clone the Repository:
git clone [your-repo-link]
cd utshacast-weather-app

2.	Open the File:
Just open the index.html file directly in your web browser to start using the app with mock data.
3.	API Key Configuration (Required for Live Data):
The application currently uses fake data to show how it works. To get live, accurate weather data, you must:
○	Sign up for a free weather API service (like OpenWeatherMap or WeatherAPI.com).
○	Get your unique API Key from their dashboard.
○	Open index.html and replace the placeholder API Key and URL constants in the <script> section with your real information.
// Inside index.html script block:
const API_KEY = 'YOUR_ACTUAL_API_KEY_HERE';
const API_BASE_URL = '[https://api.openweathermap.org/data/2.5/weather](https://api.openweathermap.org/data/2.5/weather)'; 

🚀 Future Enhancements
If you want to improve this project further, here are a few ideas:
1.	Add a 5-day forecast display.
2.	Implement Geolocation to automatically detect the user's current location on load.
3.	Introduce a unit toggle button (Celsius/Fahrenheit).
4.	Replace the current image placeholders with actual weather icons based on the API response codes.
🖼️ Preview
