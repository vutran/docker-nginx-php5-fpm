# [Ubuntu 14.04 LTS + Nginx + PHP5-FPM](https://registry.hub.docker.com/u/vutran/ubuntu-trusty-nginx-php5-fpm/)

This will install Nginx, PHP5-FPM on a Ubuntu 14.04 LTS server.

-----

To pull this image from Docker Hub:

	docker pull vutran/ubuntu-trusty-nginx-php5-fpm

To run an instance of this image:

	docker run -d -P vutran/ubuntu-trusty-nginx-php5-fpm

To mount a volume to the container:

	docker run -d -P -v /src/html:/var/www/html vutran/ubuntu-trusty-nginx-php5-fpm
