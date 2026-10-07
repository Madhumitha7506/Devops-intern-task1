# DevOps Internship - Task 1

A simple Flask "Hello World" app, containerized with Docker.

## Tech used
- Python 3.12, Flask
- Docker
- Git and GitHub

## Run with Docker
    docker build -t hello-devops .
    docker run -p 5000:5000 hello-devops

Then open http://localhost:5000 in your browser.

## Project structure
    devops-internship-task1/
    app/app.py
    Dockerfile
    requirements.txt
    .gitignore
    README.md
    docs/screenshots/
