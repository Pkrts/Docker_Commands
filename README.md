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

--->how to run
docker run mysql
--->you can run by image id also
docker run 91b4

----> how to list all the container 
docker ps -a

-->how to de;lete the container
docker rm containerid
e.g docker rm 7256

-->again you can check by 
docker ps -a

--> hwo to delete all the container that is running
docker rm $(docker ps -a -q)

-->now you can see all the  containers are deleted.
docker ps -a

-->how to delet image
docker rmi imageid

e.g docker rmi 91b53

-->now you can see image is deletd by 
docker image ls



