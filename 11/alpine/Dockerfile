FROM node:11-alpine

LABEL maintainer="m@abreto.net"

RUN npm config set registry 'https://registry.npm.taobao.org' \
    && npm i -g cnpm \
    && yarn config set registry 'https://registry.npm.taobao.org'
