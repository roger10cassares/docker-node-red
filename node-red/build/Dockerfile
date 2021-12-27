FROM nodered/node-red:2.1.4-1-14

MAINTAINER roger10cassares <roger10cassares@gmail.com>

USER root

RUN npm install -g node-red-admin

RUN apk update \
    && apk add tzdata

ENV TZ=America/Sao_Paulo