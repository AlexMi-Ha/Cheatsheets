# Docker Instructions



## Important Commands

docker ...

| Command                        | Description                                 |
| ------------------------------ | ------------------------------------------- |
| [build](#docker-build)         | Build an image from an Dockerfile           |
| [container](#docker-container) | Manage containers                           |
| [exec](#docker-exec)           | Execute commands inside a running container |
| [image](#docker-image)         | Manage images                               |
| [kill](#docker-kill)           | Kill running containers                     |
| [network](#docker-network)     | Manage networks                             |
| [ps](#docker-ps)               | List running containers                     |
| [rm](#docker-rm)               | Remove container                            |
| [rmi](#docker-rmi)             | Remove image                                |
| [run](#docker-run)             | Run a new container                         |
| [start](#docker-start)         | Start stopped containers                    |
| [stop](#docker-stop)           | Stop running containers                     |



### docker build

`docker build [OPTIONS] PATH | URL | -`

Options:

| Name, Shorthand | Descritpion                               |
| --------------- | ----------------------------------------- |
| --add-host      | Add a custom host to IP mapping (host:ip) |
| --file, -f      | Path to Dockerfile                        |
| --network       | Set network mode for later RUN cmd        |
| --tag, -t       | Tag for the image                         |

--add-host host.docker.internal:host-gateway   :  Adds "localhost" of the host to the container



### docker container

`docker container COMMAND`

Commands:

| Command | Description               |
| ------- | ------------------------- |
| ls      | List all containers       |
| prune   | Remove stopped containers |

`docker container prune [OPTIONS]`

Options:

| Name, Shorthand | Description                               |
| --------------- | ----------------------------------------- |
| --filter        | Provide filter (e.g. 'until=<timestamp>') |
| --force, -f     | Do not prompt for confirmation            |

### 

### docker exec

`docker exec [OPTIONS] CONTAINER COMMAND [ARG...]`

Options:

| Name, Shorthand   | Description                      |
| ----------------- | -------------------------------- |
| --detach, -d      | Run command in the background    |
| --env, -e         | Set environment variables        |
| --interactive, -i | Keep STDIN open                  |
| --privileged      | Give priviliges to the command   |
| --tty, -t         | Allocate a pseudo-TTY (Terminal) |

### 

### docker image

### docker kill

### docker network

### docker ps

### docker rm

### docker rmi

### docker run

### docker start

### docker stop
