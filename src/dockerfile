FROM node:19-alpine

COPY package.json /app/
COPY src /app/

WORKDIR /app

RUN npm cache clean --force
RUN npm install

CMD [ "node","server.js" ]