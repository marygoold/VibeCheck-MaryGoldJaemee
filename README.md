VibeCheck

VibeCheck 411L is a simple full-stack web application built for CPE 411L that demonstrates frontend and backend interaction using HTML, JavaScript, Node.js, and Express. Users can click buttons on the frontend to fetch dynamic responses from a REST API.

The application features random fortune messages, random programming jokes, mood-based responses for happy, tired, and stressed moods, a smash counter that increments via POST requests, and a secret endpoint that requires a code. All responses are provided in JSON format.

The backend is built with Node.js and Express, and uses CORS to allow requests from the frontend. The frontend consists of an HTML page with buttons and an output area, along with a JavaScript file that handles API calls and renders the results.

To run the project, first install the necessary dependencies using Node.js, start the backend server on localhost, and then open the HTML page in a browser. The frontend communicates with the backend to fetch data and display it in real time.

All data is stored in memory and will reset when the server restarts. The project is designed for educational purposes and local development.
