FROM node:14

WORKDIR /app

COPY client/package*.json ./

RUN npm install

COPY client/ .

RUN npm run build

EXPOSE 80

CMD ["npm", "start"]
