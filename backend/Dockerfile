FROM node:18-alpine

WORKDIR /app

COPY package.* .

RUN npm install

COPY . .

EXPOSE 80

CMD [ "npm", "start" ]