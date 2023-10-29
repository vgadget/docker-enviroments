FROM node:18.18.1-alpine3.18

WORKDIR /app

COPY package.json .

RUN npm install -g npm@latest

RUN npm install -g @angular/cli

RUN npm install

EXPOSE 4200