## Docker build image

> ``docker build . -t testdockerimage``

## Docker run container

> ``docker run -d --name testdockercontainer testdockerimage``

## Docker stop one container

> ``docker stop testdockercontainer``

## Docker stop all containers

> ``docker stop $(docker ps -qa)``

## Docker remove container

> ``docker rm testdockercontainer``

## Docker remove all containers

> ``docker rm $(docker ps -qa)``

## Docker remove image

> ``docker rmi testdockerimage``

## Docker remove all images

> ``docker rmi $(docker images -qa)``

