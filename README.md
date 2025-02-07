This repository uses Github Action to build lean4 nightly and push images to https://hub.docker.com/repository/docker/chiungyi/lean4/general

You can also build the image locally:
```
docker build -t chiungyi/lean4:nightly .
```
and push the image to the Docker hub
```
docker push chiungyi/lean4:nightly
```
