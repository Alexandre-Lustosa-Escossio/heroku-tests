FROM node:alpine

WORKDIR /app

COPY app-heroku-ci-cd/package.json .

RUN npm install

COPY . .

CMD ["node", "index.js"]