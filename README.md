## Ubuntu Dockerfile


This repository contains **Dockerfile** of :

1. [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/ubuntu/)

2. [Elasticsearch](http://www.elasticsearch.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/elasticsearch/) 

3. [Node.js](http://nodejs.org/)

all published to the public [Docker Hub Registry](https://registry.hub.docker.com/)

### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/jbng/nodejs-es/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull jbng/nodejs-es`

   (alternatively, you can build an image from Dockerfile: `docker build -t="jbng/nodejs-es" github.com/jbng/nodejs-es`)


### Usage

    docker run -it --rm jbng/nodejs-es
