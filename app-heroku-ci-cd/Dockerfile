FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD ["node", "app-heroku-ci-cd/index.js"]