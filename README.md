use follow command to make image and container

cd /usr/docker/  ##Dockerfile's location

docker build -t vert .

docker image ls

docker run --name mywebserver -d -p 8080:8080 vert

docker container ls