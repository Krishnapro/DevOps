## Docker Basic

- To check Docker vesrion

```
docker version
```

- To check all the available images

```bash
docker images
```

- Pull/Download the image from the Docker registry/Hub to local machine.

```bash
docker pull <image name>
//Eg: docker pull mysql
```

- To run the images
  - Additional flags
    - `-it` - For interactive environment
    - `-d` - To run in detached mode 
    - `-p <Host port:container port>` - To forward the port
        ```bash
        E.g.- docker run -d -p 8080:80 nginx
        ``` 
```bash
docker run <image_name>
// E.g - docker run hello-world
```
- To check all the running images
```bash
docker ps
```
- To see all the container list 
  
```bash
docker container ls
```
- Attached bash cell to running container
```bash
docker exec -it <container_id> bash
```
- To check logs 
```bash
docker ps -a
```
- To delete all the stop container 
```bash
docker container prune -f
```
- Check log of container 
```bash
docker logs <container-id/name>
```
- To start the container 
```bash
docker start <container-id/name>
```
- To stop the container 
```bash
docker stop <container-id/name>
```
- To remove the container
```bash
docker rm <container-id/name>
```
- To remove the image
```bash
docker rmi <image-name> -f
```
- To share the container with others
```bash
docker commit -m "commit message" <container-id> <imagen-name:version>
// E.g - docker commit -m "added name.txt file" a17b78de1961 name_ubuntu:1.01
```
- To get id of all the images
```bash
docker images -q
```
- To delete all the images at once
```bash
docker rmi $(docker images -q)
```
- Creating our own image and container
```bash
step 1 - create Docker file (and write comand)
step 2 - docker build -t <image-name:verison> <path of docker file>
step 3 - docker run <image-name>
```


