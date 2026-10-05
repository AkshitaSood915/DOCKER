# Base Image
FROM node:20.17.0-alpine3.19

WORKDIR /home/app/

COPY package-lock.json package-lock.json
COPY package.json package.json

RUN npm install

# Copying the source code to docker image
COPY index.js index.js

COPY Dockerfile Dockerfile