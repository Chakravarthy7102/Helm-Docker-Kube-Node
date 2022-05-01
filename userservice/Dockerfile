FROM node:gallium-slim
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY userservice /app/userservice
EXPOSE 4000
CMD [ "npm","run","start:userservice" ]
