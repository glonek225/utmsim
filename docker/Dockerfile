FROM node:latest

WORKDIR /opt/ops

COPY . /opt/utmsim

RUN npm install

EXPOSE 8080

CMD node server.js