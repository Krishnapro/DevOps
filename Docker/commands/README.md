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