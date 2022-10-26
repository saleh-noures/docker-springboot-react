# Docker Spring Boot and React sample project

## Spring Boot (The backend)
### To build an image from the Dockerfile: 
`docker build -t dockertestbackend:latest .`

### To run a container from the image:
`docker run -p 8080:8080 dockertestbackend`


## Spring Boot (The frontend)
### To build an image from the Dockerfile:
`docker build -t dockertestfrontend:latest .`

### Getting Started with Create React App
`docker run --name dockertestfrontend -d -p 3000:3000 dockertestfrontend`

## Run full stack (docker-compose.yaml) 

### to build images from dockerfiles and then run containers from the images:
`docker-compose up`

### To top the containers
`docker-compose down`