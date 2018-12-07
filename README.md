docker stop $(docker ps -aq) <br/>
docker rm $(docker ps -aq) <br/>
docker volume rm $(docker volume ls) <br/>
docker network prune
