### Docker

`docker build -t jasim101/posts` Build an image based on the dockerfile in the current directory. Tag it as `jasim101/posts`

`docker run [image id or image tag]` Create and start a container based on the provided image id or tag.

`docker run -it [image id or image tag] [cmd]` Create and start container, but also override the default command.

`docker run -p 8080:8080 [image id or image tag]` Create and start a container based on the provided image id or tag with specified ports(local-port:container-port).

`docker ps` Print out information about all of the running containers.

`docker exec -it [container id] [cmd]` Execute the given command in a running container

`docker logs [container id]` Print out logs from the given container

`docker system prune` Removed all stoped/exited container

`docker stop [container_id]` Stop the container having a clean up process

`docker kill [container_id]` Forcefully killed without resource clean up

`docker start -a [container_id]` Start a container

`docker exec -it [container id] sh|zsh|bash|powershell`

## Kubernetes

`Kubbernets Cluster` A collections of nodes + a master to manage them.

`Node` A virtual machine that will run our containers.

`Pod` More or less a running container. Technically, a pod can run muitiple containers.

`Deployment` Monitors a set of pods. make sure they are running and restarts thhem if they crash.

`Service` Provides an easy-to-remember URL to access a running container.
