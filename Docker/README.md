## Docker

## What is Docker?
Docker is a container platform that allows you to build,test and deploye applications quickly. A Developer defines all the applications and it's dependencies in docker file which is then used to build Docker images that defines a Docker container. Doing this ensure that your applications will run in any environment.

## Docker Images

![Image of Docker images](docker_images.png)

## Architechture of Docker

Docker user client-server architechture.The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon.

<img src="docker_architechture_image.png">

### Docker Daemon:
Docker daemon (`dockerd`) listen for Docker API requests and manage docker objects such as images, containers, networks and volumes. A Daemon can also communicate with other daemon to manage docker services.

### Docker Client:
Docker client is command line interface that allow users to interact with Docker. When you use commands such as `docker run`, the client sends these commands to `dockerd` which carries then out.

### Docker registry:
A Docker registry stores Docker images. Docker Hub is a public registry that anyone can use, and Docker looks for images on Docker Hub by default.

### Docker Objects:
When you use Docker, you are creating and using images, containers, networks, volumes, plugins, and other objects. This section is a brief overview of some of those objects.

