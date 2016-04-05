# Sample Spring Boot Configuration Service

## To Build into Docker using Maven

First make sure you're running in an environment that has docker available to you. Then execute:

$ mvn package docker:build

Once completed you will have an antifragilesoftware/simple-boot-configuration-server image available, as seen by executing:

$ docker images

```
REPOSITORY                         TAG                 IMAGE ID            CREATED             SIZE
antifragilesoftware/simple-boot-configuration-server   latest              6efd07dc12fc        5 seconds ago       667.1 MB
```
