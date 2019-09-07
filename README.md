# sport-lottery-predict
Predict sport lottery


## Docker environment
To use a Docker container with Jupyter notebook and all dependencies required for the project.

#### How to run docker 
```sh
docker pull a5520592/sport
```
```sh
docker run -it -p 8080:8080 --name sport -v $PWD:/root/sport a5520592/sport
```

check docker container
```sh
docker ps
```

check docker images
```sh
docker images
```

stop and remove an container
```sh
docker stop <container id>
```

```sh
docker rm <container id>
```
