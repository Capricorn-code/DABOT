FROM node:20.9.0

WORKDIR /app

COPY package*.json ./

RUN npm i -g @nestjs/cli

RUN npm install

COPY . .

CMD ["npm", "run", "start"]