# Flask on Docker
**Tutorial: https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/**

This project containerizes a Flask web application using Docker, integrating PostgreSQL as the database, Gunicorn as the WSGI server, and Nginx as a reverse proxy for production environments. It also covers serving static and user-uploaded media files via Nginx.
It's designed to provide a **production-ready** containerized environment for Flask applications. By utilizing **Docker** and **Docker Compose**, it ensures scalability, ease of deployment, and a seamless integration of essential services like PostgreSQL, Gunicorn, and Nginx.

## Features
- **Flask**: Manages backend logic and application endpoints.
- **PostgreSQL**: Provides a robust, scalable database for storing application data.
- **Gunicorn**: Efficiently serves the Flask application in production.
- **Nginx**: Acts as a reverse proxy, forwarding client requests and handling static/media file serving.
- **Docker Compose**: Simplifies orchestration of services for easy deployment and scalability.

## Dependencies
- **Flask** v2.3.2
- **Docker** v23.0.5
- **Python** v3.11.3

![Screen Recorded Image Upload](https://github.com/user-attachments/assets/44f50b5f-80fa-44f1-bb80-2290ee28a99d)

## Build
Running docker-compose up --build rebuilds the Docker images (if there are any changes) and starts all the services defined in the docker-compose.yml file. This command sets up the environment, initializing containers for the application, database, and other services, and makes the app accessible at http://localhost:1039
