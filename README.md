# Gitlab on Docker
This tutorial is based on the documentation on [Docker-Gitlab on github ](https://github.com/sameersbn/docker-gitlab).
## Preparation
Docker is installed on your system. You will find the installation description under [Docker-Installation](https://docs.docker.com/windows/).

* Docker host creation
```shell
docker-machine create -d virtualbox \
--virtualbox-cpu-count "2" \
--virtualbox-memory "8192" \
--virtualbox-disk-size "40000" \
dhost1
```
* Configuration of the shell
```shell
eval $(docker-machine.exe env dhost1)
```

## Gitlab Installation & Configuration

1. Pull the latest image version from [Dockerhub](https://hub.docker.com/r/sameersbn/gitlab/).
```shell
docker pull sameersbn/gitlab:latest
```

```python
print 4 +3 ;
for x in test:
  pass 

```
