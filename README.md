# Flask on Docker
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

