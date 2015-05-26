# [Ubuntu 14.04 LTS + Nginx + PHP5-FPM](https://registry.hub.docker.com/u/vutran/docker-nginx-php5-fpm/)

This is a simple container with Nginx, PHP5-FPM, and Ubuntu 14.04.

-----

To pull this image from Docker Hub:

	docker pull vutran/docker-nginx-php5-fpm

To run an instance of this image:

	docker run -d -P vutran/docker-nginx-php5-fpm

To mount a volume to the container:

	docker run -d -P -v /src/html:/var/www/html vutran/docker-nginx-php5-fpm
