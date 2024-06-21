FROM node:lts-alpine

WORKDIR /app

COPY . .

RUN npm install && npm run build

EXPOSE 1234

CMD ["node", "server.js"]