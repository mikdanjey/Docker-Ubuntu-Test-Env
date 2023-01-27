# Docker Ubuntu Test Env

`docker ps -a`

`docker-compose up`

`docker-compose up -d`

`docker-compose down`

`docker container prune --filter "until=0m"`

`docker volume prune --filter "label!=keep"`


## Quick Start
`docker run --name="my_ubuntu_env" -it -d ubuntu:focal bin/bash`

`docker exec -it my_ubuntu_env bin/bash`
