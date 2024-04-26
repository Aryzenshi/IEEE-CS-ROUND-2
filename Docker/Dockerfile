FROM node:21-alpine

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 3000

ENV NAME dockerproject

CMD ["npm", "start"]