FROM node:alpine3.21

WORKDIR /app

COPY package.json .

RUN npm install

COPY ./tasks-app.js ./
COPY ./tasks ./tasks

EXPOSE 3002

CMD [ "node", "tasks-app.js" ]