# DevOps CI/CD Pipeline

## Project Overview

This project demonstrates a DevOps CI/CD pipeline for a Python Flask application using GitHub Actions, Docker, and Docker Compose.

## Technologies Used

- Python
- Flask
- Git
- GitHub
- GitHub Actions
- Docker
- Docker Compose

## Application

The Flask application provides:

- Home endpoint: `/`
- Health endpoint: `/health`

## CI/CD Pipeline

The GitHub Actions workflow performs:

1. Checkout source code
2. Set up Python
3. Install dependencies
4. Test the application
5. Build the Docker image

## Docker Deployment

Docker Compose is configured to run the Flask application on:

`http://localhost:5000`

## Project Structure

```text
.github/
└── workflows/
    └── ci.yml

app.py
requirements.txt
Dockerfile
docker-compose.yml
.gitignore
README.md