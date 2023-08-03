# Task Tracker API with PostgreSQL Backend

Welcome to the Task Tracker API coding test! This test is designed to assess your skills in creating a production-quality RESTful API using Java, PostgreSQL, and robust error handling. Please read the instructions carefully and follow the steps to complete the test.

## Programming Language to use

- Unless otherwise stated, please use JAVA.

## Problem Statement

Your task is to create a robust and production-quality RESTful API for a task tracking application using a PostgreSQL database as the backend store. The API should allow users to perform CRUD (Create, Read, Update, Delete) operations on tasks, with comprehensive error handling and data validation.

### Task Properties

Each task has the following properties:

- `id` (String): Unique identifier for the task.
- `title` (String): Title of the task.
- `description` (String): Description of the task.
- `dueDate` (Date): Due date of the task.

You need to implement the following endpoints:

1. `POST /tasks`: Create a new task.
2. `GET /tasks/{id}`: Retrieve a task by its ID.
3. `GET /tasks`: Retrieve a list of all tasks.
4. `PUT /tasks/{id}`: Update an existing task by its ID.
5. `DELETE /tasks/{id}`: Delete a task by its ID.

### Instructions

1. Set up a PostgreSQL database. Create a table named `tasks` with columns `id`, `title`, `description`, and `due_date`.
2. Implement comprehensive error handling for various scenarios, including invalid input data, database errors, and unexpected situations.
3. Use appropriate HTTP status codes and response messages to communicate errors clearly to clients.
4. Implement data validation to ensure that only valid and properly formatted data is stored in the database.
5. Implement appropriate logging mechanisms to capture errors and important events.
6. Write clean, well-documented, and modular code following best practices for Java development.
7. Include unit tests and integration tests to ensure the correctness of your API and its error-handling capabilities.
8. Include detailed instructions in the `README` file on setting up the database, building, testing, and running your API.
9. Once you're done, share the link to your repository with us.

## Evaluation Criteria

You will be evaluated based on:

1. Correctness and completeness of the implemented API endpoints with PostgreSQL integration and robust error handling.
2. Comprehensive error handling and data validation for various scenarios.
3. Effective usage of HTTP status codes, response messages, and logging mechanisms.
4. Code quality, including readability, modularity, adherence to best practices, and proper use of design patterns.
5. Thorough unit tests and integration tests covering different error scenarios.
6. Documentation and instructions provided in the `README` file.

We're excited to review your submission and see your skills in action. Good luck!
