FROM nginx:mainline-alpine

RUN rm /etc/nginx/conf.d/*

ADD nginx.conf /etc/nginx/conf.d/

ADD index.html /var/www/example-docker/index.html
