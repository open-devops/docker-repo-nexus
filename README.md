[![Docker Automated buil](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?maxAge=2592000)](https://hub.docker.com/r/devopsopen/docker-repo-nexus/)

# Repository Management - Sonatype Nexus
Sonatype Nexus Docker Image for Artifact Repository Management of Open DevOps Pipeline

- Uses latest CentOS base image 
- Adds a staging repository

# docker pull
docker pull devopsopen/docker-repo-nexus

# docker run
docker run -d -p 9081:8081 --name nexus devopsopen/docker-repo-nexus

# web access
http://docker-host-machine-ip:9081

