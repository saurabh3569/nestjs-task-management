# NestJs Task Management
This is a sample NestJS API project that provides functionality for managing tasks and user authentication. The API includes the following controllers:

## TasksController
### Endpoints
+ GET /tasks: Retrieves a list of tasks based on the provided filters.
+ GET /tasks/:id: Retrieves a specific task by its ID.
+ POST /tasks: Creates a new task.
+ DELETE /tasks/:id: Deletes a task by its ID.
+ PUT /tasks/:id: Updates the status of a task by its ID.

## AuthControlle
### Endpoints
+ POST /auth/signup: Creates a new user account.
+ POST /auth/signin: Authenticates a user and returns an access token.

## How to Use
+ Install the required dependencies by running npm install.
+ Configure the database connection in the appropriate configuration file.
+ Run the application using npm start.
+ The API will be available at http://localhost:3000.