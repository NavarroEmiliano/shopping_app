FROM node:20-alpine

WORKDIR /usr/local/app

COPY package*.json ./

COPY . .

RUN npm install

EXPOSE 8002

CMD ["npm", "start"]
