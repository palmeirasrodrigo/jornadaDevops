FROM node:22.15

WORKDIR /app

COPY ./package.json ./

RUN npm install

COPY . .

CMD ["node", "server.js"]
