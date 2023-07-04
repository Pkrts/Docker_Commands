# Docker_Commands
----------------------------------------------
--> go to docker playground and login forst.
--> to show docker images
docker image ls

---> to pull docker any docker image --> go to dockr hub and search for image here for mysql so copy code from there and enter it.
docker pull mysql

--->to clear the screen 
clear

---> now again you can see the lsit of images
docker image ls

--->how to run any docker image so container will be created
docker run mysql
--->you can run by image id also
docker run 91b4

----> how to list all the container 
docker ps -a

-->how to delete the container
docker rm containerid
e.g docker rm 7256

-->again you can check by 
docker ps -a

--> hwo to delete all the container that is running
docker rm $(docker ps -a -q)

-->now you can see all the  containers are deleted.
docker ps -a

-->how to delete image
docker rmi imageid

e.g docker rmi 91b53

-->now you can see image is deletd by 
docker image ls

-->if you want to pull image with some tags from docker hub
docker pull ngnix:latest

use like this

-->it will all the running conaainer only
docker ps

--> it will show all the container wheayther its running or not
docker ps -a

-->how to stop running conatiner
docker stop containerid
e.g- docker stop f12d3

-->if i want  to run any image on oyther poprt coz that port is busy then(bydefault port is 8080 in windows)--known as port mapping
docker run -p 9000:8080 ngnix:latest(imagename)

---> you can see by opening other browser and typing
localhost:9000]
you will see ngnix is up and running.

--->search in chrome docker cheat sheet
you will all the commands that we are using here

--->
if you running the same image on same port you will get and error.- like port is already running.

---->how to see the logs of container
docker logs containerid
e.g docker logs fd123

--->






