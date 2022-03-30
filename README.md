# DockerTask
first i installed docker, docker-compose to the host
and i applied all the steps automatically,

although the docker compose is not working so i had to access the host myslef and run the command
also for the dockerfile too is not working with ansible command

i applied this commands to build the image and run the container

sudo docker build -t lampimage:1.0 .
sudo docker run -d -p8082:80 --name lampstack lampimage:1.0

then i accessed the container with that destination
http://18.204.7.241:8082/test.php
