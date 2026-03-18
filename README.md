# DevOps First Project

Simple Node.js application containerized using Docker.

## Run locally

Install dependencies:
npm install

Run app:
node app.js

Open browser:
http://localhost:3000

## Run with Docker

Build image:
docker build -t devops-project .

Run container:
docker run -p 3000:3000 devops-project

Open:
http://localhost:3000