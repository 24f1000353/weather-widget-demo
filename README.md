# Weather Widget

A simple, single-page responsive web application for checking current weather conditions for any city worldwide. Built with HTML, Tailwind CSS, and vanilla JavaScript, leveraging a public weather API.

## Features

*   Search weather by city name.
*   Displays current temperature and weather conditions.
*   Responsive design, adapting to various screen sizes.

## Setup

To get this widget up and running, you'll need an API key from OpenWeatherMap.

1.  **Get an OpenWeatherMap API Key:**
    *   Go to [OpenWeatherMap](https://openweathermap.org/api).
    *   Sign up for a free account.
    *   Navigate to the "API keys" tab on your profile page to find or generate your API key.

2.  **Replace Placeholder API Key:**
    *   Open the `index.html` file in a text editor.
    *   Locate the line `const API_KEY = 'YOUR_OPENWEATHER_API_KEY';`.
    *   Replace `'YOUR_OPENWEATHER_API_KEY'` with the actual API key you obtained from OpenWeatherMap.

## Usage

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Enter City Name:** Type the name of a city into the input field.
3.  **Get Weather:** Click the "Get Weather" button. The current temperature and conditions for that city will be displayed.

## Technologies Used

*   **HTML5:** For the basic structure of the web page.
*   **Tailwind CSS:** A utility-first CSS framework for building responsive and modern designs.
*   **JavaScript (Vanilla):** For fetching data from the API and dynamically updating the UI.
*   **OpenWeatherMap API:** A public API used to retrieve weather data.
