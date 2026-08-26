# YelpCamp

YelpCamp is a fullstack web application for discovering, sharing, and reviewing campgrounds.

The project is currently a work in progress. I’m using it to deepen my understanding of fullstack development by building a complete application with authentication, persistent data, server-side routing, validation, and user-generated content.

## Current Features

* Browse available campgrounds
* View detailed campground pages
* Create new campground listings
* Edit and delete existing listings
* Server-side validation and error handling

## Tech Stack

* **JavaScript**
* **Node.js**
* **Express**
* **MongoDB**
* **Mongoose**
* **EJS**
* **Bootstrap**

## Project Status

This project is still under active development.

## What I’m Learning

Through this project, I’m practicing how to structure and connect the different parts of a fullstack application, including:

* Designing RESTful routes
* Working with relational-style data in MongoDB
* Managing user sessions and authentication
* Implementing authorization rules
* Handling forms and server-side validation
* Building reusable server-rendered views
* Organizing Express middleware
* Handling application errors
* Managing environment variables and external services
* Taking an application from local development toward production

## Running the Project Locally

Clone the repository:

```bash
git clone <your-repository-url>
cd YelpCamp
```

Install dependencies:

```bash
npm install
```

Create the required environment variables in a `.env` file.

For example:

```env
DATABASE_URL=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```

Additional environment variables may be required as development continues.

Start the application:

```bash
npm start
```

Then open the local development URL shown in the terminal.

## Notes

The application is evolving as I continue adding features, refactoring existing code, and improving the overall user experience.

Because the project is still in progress, some functionality may change or be incomplete.
