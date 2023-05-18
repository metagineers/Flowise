# WARNING
# Not Ready Yet

FROM node:18-alpine

USER root

RUN apk add --no-cache git
RUN apk add --no-cache python3 py3-pip make g++

# You can install a specific version like: agicrypto@1.0.0
RUN npm install -g agicrypto

WORKDIR /data

CMD "flowise"