# Simple Nginx Website Docker Container

This project contains a Dockerfile for creating a Docker container that runs a simple Nginx website with a "Hello, World!" page.

## Prerequisites

- Docker installed on your machine.

## Project Structure

- `Dockerfile`: Contains the commands to assemble the Docker image.
- `nginx.conf`: Nginx server configuration file.
- `index.html`: The HTML file for the "Hello, World!" page.

## Building the Docker Image

To build the Docker image, navigate to the project directory and run the following command:

```bash
docker build -t my-nginx .
```

## Running the Docker Container

To run the Docker container, use the following command:

```bash
docker run -p 8080:80 my-nginx
```

## Authors

* **Prashant Piprotar** - - [Prash+](https://github.com/prashplus)

For more Tech Stuff
### http://prashplus.blogspot.com
