FROM node:20-alpine

WORKDIR /usr/local/app

COPY package*.json ./

COPY . .

RUN npm install

EXPOSE 8003

CMD ["npm", "start"]
