FROM node:20-bullseye


RUN npm install -g nodemon

WORKDIR /app

COPY . .

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "node", "server.js" ]