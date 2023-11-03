# Node.js-Web-Application
## Description
This is a Containerized Node.js Web Application built using the node:19-alpine Docker image. It is a simple web application that responds with "Welcome to my awesome app!" when you access the root URL. You can use this as a starting point to build and deploy your own Node.js web applications in a containerized environment.

## Prerequisites
Docker: Ensure that you have Docker installed on your system. You can download and install Docker from Docker's official website.
Getting Started
Follow these steps to get your Node.js Web Application up and running in a Docker container.

## Clone this repository to your local machine:
git clone (https://github.com/JeffreyOmoakah/Node.js-Web-Application.git)

## Navigate to the project directory:
cd nodejs-web-app

## Build the Docker image:
docker build -t my-node-app .

## Run the Docker container:
docker run -d -p 3000:3000 my-node-app

Open your web browser and visit http://localhost:3000 to access your Node.js web application.

Usage
This Node.js web application is a basic example. You can customize and expand it by modifying the code in the app directory. Key components include:

app/index.js: The main Node.js application file.
app/public/: This directory can hold static assets (CSS, JavaScript, images, etc.) for your web application.
Dockerfile: The Dockerfile used to build the Docker image for your application.
Feel free to make changes and add more routes and functionality to suit your project's requirements.

Docker Image
The Docker image for this application is based on the node:19-alpine image and includes your Node.js application code and dependencies.

Acknowledgments
This project was created using Node.js and Docker, with inspiration from various open-source projects and online tutorials.

If you have any questions or need assistance, please don't hesitate to reach out.
