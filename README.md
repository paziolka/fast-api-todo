# To-Do List Application with FastAPI

This is a simple to-do list application built using FastAPI in Python.

## Features

- **FastAPI**: Utilizes the FastAPI framework for building APIs in Python.
- **Automatically Generated JSON File**: Access the automatically generated JSON file at [http://127.0.0.1:8000/openapi.json](http://127.0.0.1:8000/openapi.json) to explore the API schema.
- **Interactive API Documentation**: Test the API using the interactive documentation available at [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs). This documentation allows you to make requests and see responses in real-time.
- **Alternative Documentation with ReDoc**: For a more structured view of the API documentation, visit [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc) which provides a clearer and more organized display of the API endpoints.

## Getting Started

1. Clone this repository.
2. Run the FastAPI application using `uvicorn main:app --reload`.
3. Access the API documentation and interact with the endpoints as needed.

## API Endpoints

- **GET /tasks**: Retrieve all tasks.
- **GET /tasks/{task_id}**: Retrieve a specific task by ID.
- **POST /tasks**: Create a new task.
- **GET /tasks?limit={limit}**: Retrieve a limited number of tasks.

## Dependencies

- FastAPI
- Uvicorn
- Pydantic

## Author

I've happiliy built it on the basis of [this youtube tutorial](https://www.youtube.com/watch?v=iWS9ogMPOI0).
