VibeCheck

VibeCheck is a simple full-stack web application built for CPE 411L that demonstrates frontend and backend interaction using HTML, JavaScript, Node.js, and Express. Users can click buttons on the frontend to fetch dynamic responses from a REST API.

The application features random fortune messages, programming jokes, mood-based responses for happy, tired, and stressed moods, a smash counter that increments via POST requests, and a secret endpoint that requires a code. All responses are provided in JSON format.

The backend is built with Node.js and Express and uses CORS to allow requests from the frontend. The frontend consists of an HTML page with buttons and an output area, along with a JavaScript file that handles API calls and displays the results.


Run Steps

1. Make sure Node.js is installed on your computer.
2. Open a terminal and navigate to the backend folder.
3. Install the required packages by running:

npm install express cors

4. Start the backend server by running:

    node server.js
   
The server will run at http://localhost:3000.


6. Open the frontend/index.html file in your browser.
  • Alternatively, you can use a local server such as:

    npx serve frontend

7. Click the buttons on the page to interact with the backend API and see the responses.

  API Endpoints

• GET /api/fortune – Returns a random fortune message.
• GET /api/joke – Returns a random programming joke.
• GET /api/vibe?mood=happy|tired|stressed – Returns a message based on the selected mood.
• POST /api/smash – Increments the smash counter and returns the updated value.
• GET /api/smashes – Returns the current smash counter value.
• GET /api/secret?code=411L – Returns a secret message if the correct code is provided.

All data is stored in memory and resets when the server restarts. The project is designed for educational purposes and local development.
