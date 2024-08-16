# Welcome to Docker

This is a repo for new users getting started with Docker.

You can try it out using the following command.
```
docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker
```
And open `http://localhost:8088` in your browser.

# Building

Maintainers should see [MAINTAINERS.md](MAINTAINERS.md).

Build and run:
```
docker build -t welcome-to-docker . 
docker run -d -p 8088:3000 --name welcome-to-docker welcome-to-docker
```
Open `http://localhost:8088` in your browser.

#Important Notice

 ## __[Docker-Get-started](https://github.com/docker/welcome-to-docker)__ - The reasoces used i was able to get the from the link connected to the clickable text at the begining of this point.
 >>To clone the repository use the following code:
 ``` Dockerfile
    git clone https://github.com/docker/welcome-to-docker
 ```