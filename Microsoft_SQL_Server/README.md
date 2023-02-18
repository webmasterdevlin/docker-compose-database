# Sample Docker-Compose files

![Docker](docker.jpeg)

#### start

```zsh
$ docker-compose up
```

#### Install or update DotNet Core CLI

```
$ dotnet tool install --global dotnet-ef
$ dotnet tool update --global dotnet-ef
```

#### DotNet Core commands

```zsh
$ dotnet ef migrations add initial
$ dotnet ef database update
$ dotnet dev-certs https --clean
$ dotnet dev-certs https
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
