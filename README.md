# zeppelin-spark-docker
Docker file for Apache Zeppelin and Apache Spark

![Docker Image CI](https://github.com/sammyrulez/zeppelin-spark-docker/workflows/Docker%20Image%20CI/badge.svg)


## Build & Run

```
docker build -t  zeppelin:0.8.1 .
docker run -p 8080:8080 -v /my/folder/with/notebook:/zeppelin/notebook -v /my/folder/with/data/:/opt/data  zeppelin:0.8.1
```
