# NVR
## Network Video Recording service wrapped in an Ubuntu 16.04 docker container.

### Features:
	- Publish video streams
	- Record the published streams
	- Report livestream and recording start/stop events via AMQP protocol

### How to build:
	- docker build .

### How to deploy:
	- docker build -t <docker name:version>
	- docker push

### Third party libraries used:
	- NGINX server
	- NGINX RTMP module
