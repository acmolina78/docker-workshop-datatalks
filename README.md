# docker-workshop-datatalks
Create Ubuntu Docker
docker run ubuntu
terminal: docker run -it ubuntu

Create Python Docker
docker run python:3.13.11
terminal bash: docker run -it --entrypoint=bash python:3.13.11-slim

docker ps -a shows all docker instances
docker ps -aq shows all docker instances id
docker rm [id] destroys instance