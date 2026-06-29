FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT=3000
# ENV USERNAME=joydip
# ENV PASSWORD=Joydip@123
EXPOSE ${PORT}

CMD ["node","server.js"]