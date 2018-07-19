# H2 Database Dockerfile
[![Docker Automated build](https://img.shields.io/docker/automated/nwtgck/h2database.svg)](https://hub.docker.com/r/nwtgck/h2database/)

Docker image for [H2 Database](https://www.h2database.com/html/main.html)

## Run Example

```bash
docker run -it -p 9092:9092 -p 8082:8082 nwtgck/h2database -tcpAllowOthers -webAllowOthers
```

Then, you can access to <http://localhost:8082/> to see Web console.

NOTE: `-tcpAllowOthers` option is necessary to access via TCP from outside of container.
