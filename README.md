# JENKINS 
The jenkins is running on `localhost:8080`
Neither creating a network with cmd `docker create network jenkins`
we use our docker-compose in order this one. 
to create 
## 1. Docker commands

### Excecute docker compose container in detach
    docker-compose up -d

### Show running processus
    docker ps
### Show Volume's list
    docker volume ls
### Show the list of docker's container 
    docker container ls

### Show logs
    docker logs <id_container>
## 2.Install Jenkins on docker
![img.png](img.png)
![img_1.png](img_1.png)

## 3. Pipeline create successfully
![img_2.png](img_2.png)
### Downloading all dependency from maven central which can take a couple of  minutes

![img_3.png](img_3.png)

### Job Successfully done 
![img_4.png](img_4.png)
    
### Execute docker in bash mode
    docker exec -it 3c96faf9eb78  sh 
    
    docker images
![img_5.png](img_5.png)