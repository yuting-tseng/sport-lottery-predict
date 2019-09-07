# sport-lottery-predict
Predict sport lottery


## Docker environment
To use a Docker container with Jupyter notebook and all dependencies required for the project.

#### How to run docker 
`docker pull a5520592/sport`
`docker run -it -p 8080:8080 --name sport -v $PWD:/root/sport a5520592/sport`

check docker container
`docker ps`

check docker images
`docker images`

stop and remove an container
`docker stop <container id>`
`docker rm <container id>`
