# CodeAlpha Docker Web Server

## Objective

This project demonstrates how to deploy and manage a web server using Docker and Nginx. The web server hosts a simple portfolio webpage and is containerized using Docker.

## Features

* Dockerized Nginx web server
* Custom HTML portfolio page
* External CSS styling
* Port mapping from host to container
* Version controlled using Git and GitHub

## Technologies Used

* Docker
* Nginx
* HTML5
* CSS3
* Git
* GitHub

## Project Structure

```
CodeAlpha_DockerWebServer/
├── Dockerfile
├── .dockerignore
├── index.html
├── style.css
└── README.md
```

## Build the Docker Image

```bash
docker build -t my-webserver .
```

## Run the Container

```bash
docker run -d -p 8080:80 --name webserver my-webserver
```

## Docker Commands Used

```bash
docker ps
docker stop webserver
docker start webserver
docker restart webserver
docker logs webserver
docker build -t my-webserver .
docker run -d -p 8080:80 --name webserver my-webserver
```

## Output

Open the application in your browser:

```
http://localhost:8080
```

The website is successfully served by an Nginx web server running inside a Docker container.

## Learning Outcomes

* Learned Docker containerization basics.
* Created a Docker image using a Dockerfile.
* Deployed a web server inside a Docker container.
* Managed the container lifecycle.
* Monitored and verified container status.
* Applied basic Docker best practices using a `.dockerignore` file.
