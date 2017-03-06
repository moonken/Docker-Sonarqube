# Docker-Sonarqube

## Run Sonarqube on local

### Requirement:

[Docker](https://docs.docker.com/docker-for-mac/install/#download-docker-for-mac) is installed;

A Docker Deamon is running, you can use docker-machine create a local VM to host Docker server like:
```
docker-machine create --driver virtualbox default.
```
```
eval $(docker-machine env default)
```

### Start Sonarqube on local
```
cd Sonarqube
docker-compose up
```
### Check the VM IP
then open http://VM-IP:9000 to view sonarqube
