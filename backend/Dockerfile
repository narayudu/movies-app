FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["node", "server.js"]
