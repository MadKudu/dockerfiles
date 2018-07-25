# MadKudu's Dockerfiles
Dockerfiles for [MadKudu's Docker images](https://hub.docker.com/r/madkudu)

Node images are based off of [Cirlce CI's Docker images](https://github.com/CircleCI-Public/circleci-dockerfiles)

# Building
The image name and tags should be the same name as Circle CI's name and tags. For example, madkudu/node:8.10 uses circleci/node:8.10

`docker build -t=madkudu/node:{tag} .`

`docker push madkudu/node:{tag}`
