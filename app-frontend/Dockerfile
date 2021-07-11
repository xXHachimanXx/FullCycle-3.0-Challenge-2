  
FROM node:12.14.0-alpine3.11

RUN apk add --no-cache bash

USER node

WORKDIR /home/node/app

RUN ["chmod", "+x", "/home/node/app/.docker/entrypoint.sh"]