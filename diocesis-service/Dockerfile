FROM node:18

RUN mkdir -p /usr/src/app

 WORKDIR /usr/src/app

COPY src/package*.json ./

RUN npm install

COPY src/ .

EXPOSE 3000

CMD [ "npm", "run", "dev" ]