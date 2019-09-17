# Education

Table of Contents
=================
  * [What's Docker](#Docker)
  * [Docker Engine](#Docker-Engine)
  * [Docker images](#Docker-images)
  * [Basic Docker Commands](#Docker-commands)
  

What is Docker?
---------------------
Designed to make it easier to create, deploy and run applications by using containers.
Containers package up an application with all of the parts it needs.
Containers allow applications to run in a loosely isolated environment called a container.
Containers are lightweight.

Docker Engine is a client-server application:
-------------------------------------------
* The server runs as a deamon process 
* REST API
* A command line interface (CLI) client

Docker Images:
-----------------
* A Docker images is a built up from a series of layers
* Each layer represents an instruction in the image's Dockerfile
* Each layer expect the very last one is read-only.

Containers and layers: 
-----------------------
* A container create a new writable layer on top of the underlying image layers.
* The difference between a container and an image is the top writable layer.
* Data changes are stored in the writable layer
* When the container is deletedm the writable layer are also deleted.

Basic Docker Commands
--------------------

docekr attach: Attach local standard input, outut and error steams to a running container(almost like ssh)

docker build: Build an image from a Dockerfile

docker exac: Run a command in a running container

docker images: List images

docker info: Display system-wide information

docker inspect: Return low-level information about Docker objects

docker logs: Fetch the logs of a container

docker network: Manage networks

docker node: Manage Swarm nodes

docker ps: List containers

docker pull: Pull an image or a repository from a registry

docker push: Push an image or a repository to a registry

docker restart: Restart one or more containers

docker rm(rmi): remove one or more containers(images)

docker run: Run a command in a new container

docker start: Start one or more stopped containers

docker swarm: Manage Swarm

docker volume: Manage volumes


