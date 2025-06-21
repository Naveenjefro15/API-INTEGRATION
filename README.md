# API-INTEGRATION

COMPANY:CODTECH IT SOLUTIONS

NAME:NAVEEN KUMAR P

INTERN ID:CCT04DN1762

DOMAIN:FULL STACK WEB DEVELOPMENT

DURATION:4WEEKS

MENTOR:NEELA SANTOSH

##DESCRIPTION##

JEFRO Weathers is a modern, lightweight, and responsive web-based weather application designed to fetch and display real-time weather data for Indian cities. The project is built using core web technologies—HTML, CSS, and JavaScript—and integrates the OpenWeatherMap API to dynamically pull current weather information based on user input. The overall goal of this application is to provide a simple yet elegant interface for users to instantly check weather details for any city in India.

The JEFRO Weathers application is a simple yet effective web-based weather app that demonstrates the use of HTML, CSS, and JavaScript in integrating with a public API. The HTML layout is clean and semantic, beginning with a title heading `<h1>🌤 JEFRO Weathers</h1>`, which helps brand the app and enhances accessibility. Below the title, a container with the class `.weather-container` includes an input field where users can enter the name of an Indian city, a button that triggers the weather-fetching functionality, and a result container (`#weatherResult`) where weather details are displayed. The interface is responsive, ensuring usability across devices, from desktops to smartphones.

The CSS, written within a `<style>` tag, creates a visually appealing user interface. It features a linear gradient background from soft blue (#83a4d4) to aqua (#b6fbff), evoking the feeling of a fresh weather-based theme. A unique feature is the use of the `body::before` pseudo-element, which displays a large, faded watermark text "NK" centered in the background. This adds a subtle branding element without interfering with content readability. The weather container is styled to appear as a translucent card using a semi-transparent white background (`#ffffffaa`), with ample padding, rounded corners, and a soft shadow, giving it a modern card-like appearance. Input fields and buttons are uniformly styled for consistent user experience, and a media query ensures the layout adjusts gracefully for smaller screen sizes.

JavaScript is used to power the dynamic functionality of the app. An asynchronous function named `getWeather()` handles the logic. It captures the city name entered by the user, constructs a URL using that input and an API key, and makes a fetch request to the OpenWeatherMap API. The URL is crafted specifically for Indian cities using the `"IN"` country code. Upon receiving a response, the data is parsed and displayed in the result area, showing the city name, country, temperature in Celsius, weather description (like clear sky or rain), humidity percentage, and wind speed in meters per second. In case of an error—such as an invalid city name or API issue—the script catches the error and shows a friendly message in red.

For running the project in Visual Studio Code, the "Live Server" extension makes the process seamless. Simply save the code in a file named `index.html`, right-click the file in VS Code, and choose "Open with Live Server." This will automatically launch the app in a web browser. Users can then enter any Indian city name such as Mumbai, Chennai, or Delhi and click the button to see live weather data fetched directly from the OpenWeatherMap API. The JEFRO Weathers app offers a great introduction to working with APIs, front-end design, and JavaScript-based data manipulation in a web development environment.

#OUTPUT#



