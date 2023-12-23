# Movie Database Web App

## Overview

This web application is a Movie Database built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to view a list of movies, add new movies, view detailed information about a movie, edit movie details, and delete movies.

## Features

- **View Movie List:** See a list of movies with details.
- **Add Movie:** Add a new movie to the database with various details.
- **View Movie Details:** Click on a movie to view detailed information.
- **Edit Movie:** Modify details of an existing movie.
- **Delete Movie:** Remove a movie from the database.

## Technologies Used

- **Frontend:**
  - React.js
  - React Router for client-side routing
  - Axios for making HTTP requests
  - `react-datepicker` for handling date input

- **Backend:**
  - Node.js with Express.js
  - MongoDB for the database
  - Mongoose for interacting with MongoDB

## Project Structure

- **Client:** Contains the React.js frontend code.
  - Components: Reusable React components.
  - Styles: CSS files for styling components.
  - Pages: React components representing different pages.
  - App.js: Main React component and routing.

- **Server:** Contains the Node.js backend code.
  - Models: MongoDB schema models.
  - Routes: Express.js routes for handling HTTP requests.
  - Server.js: Main server file.

## How to Run

1. Clone the repository.

   cd client
   npm install

   cd ../server
   npm install
# In the client directory
npm start

# In the server directory
npm server.js start in intergrated terminal


# Project Structure

client/: Frontend React code.
components/: Reusable React components.
styles/: CSS files for styling.
pages/: React components for different pages.
App.js: Main React component and routing configuration.
server/: Backend Node.js code.
models/: MongoDB schema models.
routes/: Express.js routes.
server.js: Main server file.

Author
Timmy Makay
