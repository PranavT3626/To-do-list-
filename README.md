# Node.js ToDo App

## Overview
This project is a backend application developed using Node.js and Express.js for managing to-do notes. It provides a robust set of functionalities to create, update, retrieve, and delete to-do notes, with optional support for uploading images associated with notes. The application follows RESTful API conventions and integrates seamlessly with a PostgreSQL database to store and manage the to-do notes data.

## Features
- **Create ToDo Note**: Allows users to create new to-do notes with a title, description, and optional image upload.
- **Update ToDo Note**: Enables users to update existing to-do notes, including modifying the title, description, and associated image.
- **Get ToDo Notes (with Pagination)**: Provides a paginated list of existing to-do notes, allowing users to navigate through the notes efficiently.
- **Delete ToDo Note**: Allows users to delete existing to-do notes, removing them from the database.
- **Create Multiple ToDo Notes**: Offers the ability to create multiple to-do notes at once, facilitating bulk operations.

## Project Structure
The project follows a well-organized directory structure, separating concerns into different modules for improved maintainability and scalability. Here's a brief overview of the project structure:
- **config**: Contains configuration files, including the database configuration.
- **controllers**: Houses controller functions responsible for handling various HTTP requests and business logic.
- **middlewares**: Includes middleware functions for request validation and error handling.
- **models**: Defines database models using Sequelize ORM for interacting with the PostgreSQL database.
- **routes**: Defines route handlers for different API endpoints.
- **uploads**: Stores uploaded images associated with to-do notes.
- **utils**: Contains utility functions used across the application.
- **index.js**: Main entry point of the application.
- **package.json**: Contains metadata and dependencies information for the project.
- **README.md**: Provides essential information about the project, including setup instructions and API documentation.

## Setup Instructions
To set up the application locally, follow these steps:
1. Clone the repository.
2. Install dependencies using npm.
3. Set up the environment variables.
4. Start the application using npm.


## API Documentation
The application exposes a set of RESTful APIs for interacting with to-do notes. Below is the documentation for each API endpoint:
- **Create ToDo Note**: `POST /api/todos`
- **Update ToDo Note**: `PUT /api/todos/:id`
- **Get ToDo Notes (with Pagination)**: `GET /api/todos`
- **Delete ToDo Note**: `DELETE /api/todos/:id`
- **Create Multiple ToDo Notes**: `POST /api/todos/multiple`


## Error Handling
The application ensures robust error handling, providing appropriate error messages and status codes for various scenarios, such as invalid input data, resource not found, and internal server errors.

![Screenshot of the project](https://github.com/PranavT3626/todo-app/blob/main/Screenshot%202024-06-19%20212112.png)

