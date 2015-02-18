## Ubuntu Dockerfile

Ubuntu Dockerfile, with Moscow tzdata.


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/systemate/ubuntu/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull systemate/ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="systemate/ubuntu" github.com/systemate/ubuntu`)


### Usage

    docker run -it --rm systemate/ubuntu
