
STOP ALL CONTAINERS:  docker stop $(docker ps -aq)

REMOVE ALL IMAGES:  docker rmi -f $(docker images -a -q)

docker system prune -f -a


docker start container-name
Docker stop container-name

Docker ps -a



 



GOTO FOLDER using cd command
Example cd Desktop/mysql
START DOCKER COMPOSE:  docker-compose up -d