FROM node:lts-alpine

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm i --production
COPY . .

CMD [ "npm", "start" ]
