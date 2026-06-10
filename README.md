# Docker Assignment

## Introduction

This project demonstrates how to containerize a Node.js application using Docker and publish the image to Docker Hub.

## Application Description

The application is a simple Express.js web server.

Features:

* Displays a welcome message
* Runs on port 3000
* Lightweight and easy to deploy

## Technologies Used

* Node.js
* Express.js
* Docker
* Docker Hub
* Git
* GitHub

## Project Structure

docker-assignment/
├── app.js
├── package.json
├── Dockerfile
├── .dockerignore
└── README.md

## Build Docker Image

docker build -t nadeeshan1/docker-assignment:v1 .

## Run Docker Container

docker run -d -p 3000:3000 nadeeshan1/docker-assignment:v1

## Docker Hub Image

https://hub.docker.com/repository/docker/nadeeshan1/docker-assignment/general

## GitHub Repository

https://github.com/YOUR_USERNAME/docker-assignment

## New Techniques Learned

* Docker image creation
* Dockerfile configuration
* Container deployment
* Docker Hub image hosting
* GitHub version control

## Conclusion

This assignment demonstrates the complete workflow of containerizing an application, publishing the image to Docker Hub, and managing source code using GitHub.
