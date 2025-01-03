# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The `bug.js` file contains a route that attempts to find a user by ID but doesn't handle the case where the ID is invalid or the user isn't found.

The `bugSolution.js` file provides a corrected version with proper error handling, demonstrating best practices for robust Express.js applications.  This includes checking for non-numeric user IDs and returning appropriate HTTP status codes.