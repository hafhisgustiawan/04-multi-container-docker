FROM node:18-alpine

WORKDIR /app

COPY package* .

RUN npm install

COPY . .

CMD [ "npm", "start" ]

# ketika ingin run react di development mode ini di docker, pastikan gunakan interactive mode (cth: docker run -it) dan jangan gunakan --network karena react berjalan di browser, jadi nama container tidak bisa merepresentasikan ip dari container tsb