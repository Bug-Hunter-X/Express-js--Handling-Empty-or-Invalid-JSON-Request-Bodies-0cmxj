# Express.js: Handling Empty or Invalid JSON Request Bodies
This repository demonstrates a common issue in Express.js applications where the request body parsing fails when the request body is empty or contains invalid JSON data.  The application throws an error.  A solution is provided to gracefully handle these situations.

## Bug
The `bug.js` file contains an Express.js application that attempts to parse the JSON request body. However, it lacks proper error handling for empty or invalid JSON data.

## Solution
The `bugSolution.js` file demonstrates a robust approach that addresses the issue by adding middleware to handle errors and provide appropriate responses.

## How to run
1. Clone the repository
2. Run `npm install` to install the dependencies
3. Run `node bug.js` or `node bugSolution.js` to start the server
4. Send a POST request to `/users` with valid or invalid JSON data.