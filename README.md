# Dockerized Flask App

## Description
A simple Flask application containerized using Docker.
The app exposes one endpoint that returns:
"Hello, Velsync!"

## Steps to Run

### Build Docker Image
docker build -t flask-app .

### Run Docker Container
docker run -p 5000:5000 flask-app

### Access App
http://localhost:5000

## Output
Hello, Velsync!
