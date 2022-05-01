FROM node:gallium-slim

WORKDIR /app/

COPY package.json /app/

RUN npm install

COPY ./app/server.js .

ARG PORT

EXPOSE $PORT

CMD [ "node","server.js"]


#  docker build . --tag app:latest -f ./app/Dockerfile