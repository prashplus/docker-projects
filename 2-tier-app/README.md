# Docker Compose Setup for Frontend and Backend Services

This repository contains a simple setup for running frontend and backend services using Docker Compose.

## Services

- **Frontend**: A simple React application that fetches data from the backend when the component is mounted.
- **Backend**: An Express.js server that responds with a JSON object when a GET request is made to the `/data` endpoint.

## Dockerfiles

- **Dockerfile-frontend**: Used to build the Docker image for the frontend service.
- **Dockerfile-backend**: Used to build the Docker image for the backend service.

## Docker Compose

The `dcompose.yaml` file is used to manage these two services and ensure they can communicate with each other.

## Getting Started

1. **Build and run the services**: You can start the services with the following command:
    ```bash
    docker-compose up --build
    ```

2. **Access the applications**: The frontend application is running on port 3000 and the backend application is running on port 5000.


## Note

This is a very basic example. Depending on your application, you might need to add more configurations such as environment variables, volumes, networks, etc. Please adjust it according to your needs.
