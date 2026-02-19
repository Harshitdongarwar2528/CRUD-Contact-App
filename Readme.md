# Contact CRUD App

A simple contact management application built using Node.js, Express, MongoDB, and Bootstrap.

## Features

* Add new contacts
* View contacts with pagination
* Edit contact details
* Delete contacts
* Server-side error handling
* Responsive UI using Bootstrap
* Pagination powered by mongoose-paginate-v2

## Tech Stack

* Node.js
* Express
* MongoDB
* Mongoose
* mongoose-paginate-v2
* Bootstrap

## Installation

1. Clone the repository
2. Navigate into the project folder
3. Install dependencies:

   ```bash
   npm install
   ```

## How to Run

1. Start the server:

   ```bash
   node app.js
   ```
2. Open your browser and visit:

   ```
   http://localhost:3000
   ```


## Pagination

Contact listing uses **mongoose-paginate-v2** to load contacts page by page for better performance and usability.

## Error Handling

The application includes centralized error handling to:

* Catch invalid routes
* Handle database and server errors
* Return user-friendly messages

