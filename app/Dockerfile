#Create a Dockerfile for the Node.js application
FROM node:18.16

WORKDIR /app

ADD . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]