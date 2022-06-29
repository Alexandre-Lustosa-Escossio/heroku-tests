FROM node:alpine

WORKDIR /app-heroku-ci-cd

COPY package.json .

RUN npm install

COPY . .

CMD ["node", "index.js"]