FROM php:8.1-apache-bookworm

WORKDIR /var/www/html

RUN apt update && \
	apt -y install git && \
	apt clean && \
	git clone https://github.com/Saulgp-daw/SSG.git . && \
	chown -R root:root .
EXPOSE 80
