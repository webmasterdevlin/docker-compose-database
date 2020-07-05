# Sample Docker-Compose files

#### start

```zsh
$ docker-compose up
```

#### remove and remove all volumes

```zsh
$ docker-compose down
$ docker-compose down -v
```

#### One liner to stop / remove all of Docker containers, images, and cache:

```zsh
$ docker stop $(docker ps -a -q)
$ docker rm $(docker ps -a -q)
$ docker rmi $(docker images -a -q)
$ docker builder prune
```

## PgAdmin

[https://www.pgadmin.org/download/](https://www.pgadmin.org/download/)
