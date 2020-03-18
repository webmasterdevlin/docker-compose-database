# Sample Docker-Compose files

#### start

```zsh
$ docker-compose up
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

#### One liner to stop / remove all of Docker containers:
```zsh
$ docker stop $(docker ps -a -q)
$ docker rm $(docker ps -a -q)
```