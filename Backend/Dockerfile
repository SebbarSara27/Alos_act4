FROM node:16
WORKDIR /api
COPY ./ ./
COPY package*.json .

RUN npm i npm@latest -g
RUN npm install
RUN npm install pm2 -g

COPY  . .

EXPOSE 3000

CMD node index.js
