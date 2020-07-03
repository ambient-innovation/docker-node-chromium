# docker-node-chromium
A docker image that is based on node but installed chromium on top. Can be used to run snapshots with chromium (e.g. react-snap).

Docker images are hosted at https://hub.docker.com/repository/docker/ambientinnovation/docker-node-chromium

## Contribute
Dockerhub automatically builds the master branch as "latest".
Please tag any change in the node version with the same tag, as node has. E.G. if you change the base image to "node:10", create a git tag "10". Dockerhub will then build a dockerimage with the same tag (ambientinnovation/docker-node-chromium:10), so users always know which node version is used.
