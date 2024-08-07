FROM node:20-alpine

WORKDIR /usr/local/app

COPY package*.json ./

COPY . .

RUN npm install

EXPOSE 8001

CMD ["npm", "start"]
