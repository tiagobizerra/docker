# Docker

### mac installation
brew install docker-machine docker docker-compose
docker-machine create -d virtualbox test	

## connect to docker
docker exec -it $container_id bash
docker-machine

### stop containers
docker stop $(docker ps -a -q)
### rm container images
docker rm $(docker ps -a -q)
