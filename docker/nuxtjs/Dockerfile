FROM node:16-alpine3.14

WORKDIR /var/www

RUN apk update && \
    npm install -g npm 

EXPOSE 80
ENV HOST 0.0.0.0