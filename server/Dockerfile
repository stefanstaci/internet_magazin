FROM node

WORKDIR /app

COPY package*.json ./

RUN npm install -g npm@9.1.3

RUN npm install nodemon

EXPOSE 8000

COPY . .

CMD ["node", "index.js"]