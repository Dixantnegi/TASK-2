# REST API CLIENT

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: DIXANT NEGI

*INTERN ID*: CT08RWI

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

The program begins by defining the API key and the base URL for the OpenWeatherMap API. A default city, Dehradun, is set, but this can be replaced with any city name. The API URL is constructed by appending the city name and API key to the base URL, along with a query parameter to return the temperature in Celsius.

The program then makes an HTTP GET request using Java's HttpURLConnection class. The response is read using a BufferedReader, and the JSON data is stored in a StringBuilder for further processing. Once the data is fetched, the program parses it using the JSONObject class from the org.json library.

From the JSON response, the program extracts key weather details, including:

City name

Current temperature

Feels-like temperature

Humidity level

Weather description (e.g., "clear sky" or "light rain")


Finally, the extracted data is displayed in a user-friendly format, making it easy to understand the current weather conditions for the selected city. The program includes basic error handling to catch exceptions if there is an issue fetching the data.

This application demonstrates key concepts of API integration, JSON parsing, and handling HTTP requests in Java. It can be improved by allowing user input for city selection, better error handling for invalid responses, and integrating additional weather parameters such as wind speed or atmospheric pressure.

OUTPUT


