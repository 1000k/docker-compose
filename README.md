docker-compose
====

Docker image for Docker Compose to run app in Docker-in-Docker environment.


Usage
----

```sh
docker run -v /var/run/docker.sock:/var/run/docker.sock -it 1000k/docker-compose docker info
```

