# Nginx : Installation guide

## Prerequisites :

Docker installed (<a href="https://github.com/Ramy99-dev/docker-training/blob/master/1.installation-guide.md">installation guide</a>)

## Installation 

1.Install official nginx docker image from Dockerhub by runing :
```
docker pull nginx:latest
```

2.Run nginx container :
```
docker run -p 80:80 nginx:latest
```


