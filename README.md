# Spring Cloud examples by MyToshika

This repository hosts the projects and their source codes written for various tutorials written in [MyToshika]

Git commands to execute in properties folder: config-git-repo
$ git init
$ git add .
$ git commit -m "initial commit"

spring.cloud.config.server.git.uri will bind the git location to look for the configuration. Here we are using local git repo but can be switched to remote got location by just changing this location.

## Development Environment

* Spring Boot [2.2.1.RELEASE]
* Spring Cloud [Hoxton.RELEASE]
* Maven 4
* JDK 8
* Eclipse Photon

## Related Tutorials

1. [Spring Cloud Config Server with Git Integration]