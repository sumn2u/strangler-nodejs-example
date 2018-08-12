# Strangler Nodejs Example

Simple demo application showing how legacy system can be re written  using strangler pattern.  
`old_pattern` folder contains legacy system and `revised_pattern` contains same system but using strangler pattern.
## Prerequisites
You will need the following things properly installed on your laptop/pc.


* [Node.js](http://nodejs.org/)
* [Docker](https://www.docker.com/)
* [Nginx](https://nginx.org/)
* [MongoDB](https://www.mongodb.com/)




## Installation

* `git clone <repository-url>` this repository
*  change into the `old_pattern` directory to run legacy system 
* `docker-compose up -d` 
*  change into the `revised_pattern` directory to run strangle pattern system
* `docker-compose up -d` 
*  to stop the docker run `docker-compose up -d` 


## Running / Development

* `docker-compose up -d`
* Visit your app at [http://localhost:8080](http://localhost:8080).
