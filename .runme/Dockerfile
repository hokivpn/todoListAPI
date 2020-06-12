FROM node:14.0.0
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT node app.js --exec babel-node --
