FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

RUN npm install mongodb

COPY . .

EXPOSE 3000

CMD [ "node", "users-app.js" ]