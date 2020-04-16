FROM node:latest

WORKDIR ./app

COPY package.json ./

RUN npm install -g

COPY ./ ./

EXPOSE 5000

CMD npm run serve