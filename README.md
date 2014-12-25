## Node.js Dockerfile


This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/jakexks/nodejs/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/python](http://dockerfile.github.io/#/python)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/jakexks/nodejs/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull jakexks/nodejs`

   (alternatively, you can build an image from Dockerfile: `docker build -t="jakexks/nodejs" github.com/jakexks/nodejs`)


### Usage

    docker run -it --rm jakexks/nodejs

#### Run `node`

    docker run -it --rm jakexks/nodejs node

#### Run `npm`

    docker run -it --rm jakexks/nodejs npm
