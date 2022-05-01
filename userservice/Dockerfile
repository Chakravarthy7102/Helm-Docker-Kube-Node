FROM node:gallium-slim
WORKDIR /app
COPY package*.json .
RUN npm install
COPY userservice /app/userservice
EXPOSE 4000
CMD [ "npm","run","start:userservice" ]
