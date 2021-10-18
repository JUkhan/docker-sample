Docker create hello-world

Docker start -a <container_id> (a0c36c81bc456

// removed all stoped container
docker system prune

Docker logs <container_id>

Docker stop <container_id> // have a clean up process

Docker kill <container_id > // forcefully killed without resource clean up

Docker exec -it <container-id> <command>

docker exec -it b5a01a0476e5 redis-cli

docker exec -it b5a01a0476e5 sh/zsh/bash/powershell

Docker run -it busybox sh

// a docker file

`FROM alpine`

`RUN apk add —update redis`

`CMD [ “redis-server” ]`

// go to path docker file

docker build .

docker build -t dockerid/imagename

Docker run <container_id>

Docker run <container_id | dockerid/imagename

Docker run -p 8080:8080 <container_id | dockerid/imagename
