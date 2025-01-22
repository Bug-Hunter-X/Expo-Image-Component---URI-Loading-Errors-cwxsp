# Expo Image Component URI Loading Errors

This repository demonstrates a common issue when using the Expo `Image` component with URIs and provides a solution to handle potential errors.

## Problem
The Expo `Image` component may fail to load images if the URI is incorrect, the server is unreachable, or due to other network or CORS-related issues. This can result in a broken or blank image placeholder in your application.

## Solution
The solution involves implementing error handling to gracefully manage these scenarios. This can include displaying a placeholder image, a loading indicator, or an error message when an image fails to load.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install the required dependencies.
4. Run `expo start` to start the Expo development server.

The `bug.js` file demonstrates the problematic scenario, while `bugSolution.js` provides a solution with error handling.