FROM node:20-alpine as builder

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

RUN npm install node-cron

CMD [ "npm","start" ]