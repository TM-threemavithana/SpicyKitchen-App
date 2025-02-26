# Build react client
FROM node:20-bullseye



# Working directory be app
WORKDIR /app

COPY package.json ./

###  Installing dependencies

RUN npm install 
# copy local files to app folder
COPY . .

EXPOSE 3000

CMD ["npm","run","start"]