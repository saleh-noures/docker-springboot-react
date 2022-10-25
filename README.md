# Docker Spring Boot and React sample project

## Spring Boot (The backend)
### To build an image from the Dockerfile: 
`docker build -t springio/gs-spring-boot-docker .`

### To run a container from the image:
`docker run -p 8080:8080 springio/gs-spring-boot-docker`


## Spring Boot (The frontend)
### To build an image from the Dockerfile:
`docker build -t myreactdocker:latest .`

### Getting Started with Create React App
`docker run --name myreactdocker -d -p 3000:3000 myreactdocker:latest`

https://medium.com/geekculture/getting-started-with-docker-in-your-react-js-application-the-basics-6e5300cf749d