# Setup postgres with docker: 
```
    docker run --rm   --name pg-docker -e POSTGRES_PASSWORD=docker -d -p 5431:5432 -v $HOME/docker/volumes/postgres:/var/lib/postgresql/data  postgres
```