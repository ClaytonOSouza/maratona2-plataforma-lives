FROM node:12.22.0-alpine3.10
RUN apk add --no-cache bash

RUN touch /root/.bashrc | echo "PS1='\w\$ '" >> /root/.bashrc

WORKDIR /app
