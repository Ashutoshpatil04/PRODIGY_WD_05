# PRODIGY_WD_05
Weather app using HTML ,CSS and Javascript 

🎯 This weather application provides real-time weather information for any location entered by the user. The app fetches weather data from a weather API and displays it in a user-friendly interface. Key features include displaying the current temperature, weather conditions, humidity . 
🎯 Tools Used
▪ HTML (Hypertext Markup Language)
Purpose: Structure and content of the web pages.
Usage: Defines the layout of the web application, including input fields, buttons, and display areas for weather information.
▪ CSS (Cascading Style Sheets)
Purpose: Style and layout of the web pages.
Usage: Defines the appearance of HTML elements, including colors, fonts, spacing, and positioning.
▪ JavaScript
Purpose: Interactivity and dynamic content.
Usage: Fetches weather data from the API and updates the web page with the retrieved information.
◼ API (Application Programming Interface)
Used API: OpenWeatherMap API
Purpose: Provides weather data for the specified city.
Usage: The JavaScript code sends a request to the OpenWeatherMap API with the city name and API key, then processes the returned data to display weather information on the web page.


Algorithm Used to Build the Application
Input Handling:
User enters a city name in the input field.
JavaScript captures the input when the "Get Weather" button is clicked.
API Request:

JavaScript constructs the API URL using the entered city name and API key.
JavaScript sends a fetch request to the OpenWeatherMap API.
Data Processing:

The API returns a JSON response containing weather data.
JavaScript extracts relevant information (e.g., temperature, humidity, weather description) from the response.
Display Update:

JavaScript dynamically updates the HTML to display the extracted weather information.
If an error occurs (e.g., city not found), JavaScript displays an error message.
This weather application demonstrates a practical use of web development technologies and APIs, creating a dynamic and user-friendly interface
