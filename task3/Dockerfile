FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package*.json ./

RUN npm install

COPY . .

EXPOSE  3032

RUN ["node", "main.js"]