# WebSphere Application Server Developer Edition Liberty image for Docker *with SSL and AdminConsole*

The [Dockerfile](Dockerfile) in this directory is used to build the `websphere-liberty:javaee7-with-admin` image on [Docker Hub] (https://hub.docker.com/r/hi5san/webshere-liberty/) based on the `websphere-liberty:javaee7` image on [Docker Hub](https://registry.hub.docker.com/_/websphere-liberty/). The image contains IBM WebSphere Application Server Developer Edition Liberty with Java EE 7 Full Platform features and an IBM Java Runtime Environment V8, with AdminConsole and external SSL (https) access enabled.

# Usage

Instructions for using the image can be found on [Docker Hub] (https://hub.docker.com/r/hi5san/webshere-liberty/) or the fork base [Docker Hub](https://registry.hub.docker.com/_/websphere-liberty/). It is possible to build the image yourself by cloning this repository, changing to the `ga/developer/javaee7-with-admin` directory and then issuing the command `docker build .`.
